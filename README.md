# CSS3
### CSS3 compatible issues
| prefix  | browser       |
|---------|---------------|
| -webkit | chrome/safari |
| -moz    | firefox       |
| -ms     | ie            |
| -o      | opera         |

check individual property compatible: https://caniuse.com/<br /> 
Note that you dont have to do this if you are using a build system like gulp and grunt<br /><br />

*box-shadow* / *text-shadow* will affect loading performan on page, try to use as less as you can <br /><br />

*color*: rbga(r, g, b, a) | a is opacity(0-1) <br /><br />

*linear-gradient* (to top, color-from), color-to, [more color]), you can also use clock wise degree as direction<br />
example: linear-gradient (to top, red 20%, yellow 80%, green 100%) from bottom to top, 0-20% red, 20%-80% red to yellow, 80-100% yellow to green <br /> <br />

*radial-gradient* (sharpe and position, color-from, color-to)
example: radial-gradient(circle [radius] at 50% 50%, color-from, color-to, [])

