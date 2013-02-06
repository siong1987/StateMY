# StateMY

StateMY is a symbol font that makes it easy to create a map of Malaysian. It is heavily inspired by the [Stately][1] project.

## Files
    map.svg      - SVG map used to create the font
    screen.css   - Base CSS for the statemy.html demo page
    statemy\     - Folder containing the web-fonts and basic CSS
    statemy.html - Basic Demo
    statemy.svg  - SVG font file
    statemy.ttf  - TrueType font file

## How-to

In order to use StateMy, you need to add the basic `statemy` folder in to your project which includes the required CSS and web font files.  Then, add the `statemy.css` to the head of your web page.

`<link rel="stylesheet" href="statemy/statemy.css">`

In your markup, you can do this:

    <ul class="statemy" id="plain">
      <li class='johor'>a</li>
      <li class='kedah'>b</li>
      <li class='kelantan'>c</li>
      <li class='melaka'>d</li>
      <li class='negeri_sembilan'>e</li>
      <li class='pahang'>f</li>
      <li class='pulau_pinang'>g</li>
      <li class='perak'>h</li>
      <li class='perlis'>i</li>
      <li class='sabah'>j</li>
      <li class='sarawak'>k</li>
      <li class='selangor'>l</li>
      <li class='terengganu'>m</li>
      <li class='kuala_lumpur'>n</li>
      <li class='labuan'>o</li>
      <li class='putra_jaya'>p</li>
    </ul>

Please notice that each character is corresponding to each state.  And, the character `q` will show you the whole Malaysia map.

## Demo

You can check out a simple demo [here][2].

##Resources

[Free Online Font Converter](http://www.freefontconverter.com) - For converting SVG to TTF  
[Font Squirrel](http://www.fontsquirrel.com/fontface/generator) - For converting TTF to web fonts (make sure you check 'no subsetting')  
[Intridea Blog: How to Make Your Own Symbol Font](http://www.intridea.com/blog/2012/4/24/symbol-font) - A good starting place

##Credits

Yee Siang
[Malaysia SVG Map](http://pws.yeesiang.com/go/system/mod/blog/code/blank_malaysia_map)

Ben Markowitz  
[twitter](http://www.twitter.com/bpmarkowitz)  
[website](http://www.benmarkowitz.com)  

Intridea  
[website](http://www.intridea.com)  

##License

MIT License. See LICENSE for details.

[1]: https://github.com/intridea/stately
[2]: http://siong1987.com/statemy