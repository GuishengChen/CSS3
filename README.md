# CSS3
### CSS3 compatible issues
| prefix  | browser       |
|---------|---------------|
| -webkit | chrome/safari |
| -moz    | firefox       |
| -ms     | ie            |
| -o      | opera         |

check individual property compatible issues: https://caniuse.com/<br /> 
Note that you dont have to do this if you are using a build system like gulp and grunt<br /><br />

*box-shadow* / *text-shadow* will affect loading performan on page, try to use as less as you can <br /><br />

*color*: rbga(r, g, b, a) | a is opacity(0-1) <br /><br />

*linear-gradient* (to top, color-from), color-to, [more color]), you can also use clock wise degree as direction<br />
example: linear-gradient (to top, red 20%, yellow 80%, green 100%) from bottom to top, 0-20% red, 20%-80% red to yellow, 80-100% yellow to green <br /> <br />

*radial-gradient* (sharpe and position, color-from, color-to)<br />
example: radial-gradient(circle [radius] at 50% 50%, color-from, color-to, [])<br/><br/>

*word-break*      word-break: break-word--- allow a word to next line if exceed the width limit<br/><br/>

*font-face* to import a new font<br/>
@font-face{                               
    font-family:"font-name";
    src: "./newfont.ttf"
    src: "./newfont.eot" format('eot")---to tell brower the format to read
    }   then you can use---> p{ font-family: "font-name";}<br/>
reference: https://www.w3cplus.com/content/css3-font-face
    <br/><br/>
*border-image* border-image{url: "./bg.jpg" 100 repeat/round/strech}  bg.jpg divided by 100<br/><br/>
*background-origin* change background photo position, default start at padding position, you can use background-origin: border-box to start with the box model, some other value could be padding-box(default) content-box<br/><br/>

*background-clip* to cut the piece of photo, such as only display photo in content-box, exceeded part is hidden, default is no-clip<br/><br/>

*background-size* auto: do not change the origin photo, 100px 50px (height and width), cover: fill the background, contain: contain the photo <br/><br/>

*background-position* center center; 100px 100px

