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

##Credits

Ben Markowitz  
[twitter](http://www.twitter.com/bpmarkowitz)  
[website](http://www.benmarkowitz.com)  

Intridea  
[website](http://www.intridea.com)  

##License

MIT License. See LICENSE for details.

[1]: https://github.com/intridea/stately