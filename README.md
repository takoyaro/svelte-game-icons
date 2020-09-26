# Svelte Game-Icons

svelte-game-icons is a simple component wrapping the [game-icons](https://github.com/game-icons/icons) library for easy use in your Svelte projects.

# Import
Import only the icons you need where you need them by using the following syntax:
`import {IconName} from 'svelte-game-icons';`

# Icons naming convention
All icons start with an uppercase letter and those that have multiple words are combined with no space nor hyphen but each word starts with an uppercase letter, for example:
The `dark-squad` icon (called Dark squad on [Game Icons website](https://game-icons.net/1x1/lorc/dark-squad.html)) is named `DarkSquad`.

Finally, all icons starting with `3d` have been renamed with `ThreeD` instead: 
`3d-glasses` becomes `ThreeDGlasses`.

# Usage
Possible props for icons are:
| Prop        | Values                  | Example                | Notes                                                                           |   
|-------------|-------------------------|------------------------|---------------------------------------------------------------------------------|
| bg          | Any valid color string  | `#fff`                 | This is the color of the square background of the icon                          |
| fg          | Any valid color string  | `rgba(212,32,124,0.5)` | This is the color of the icon itself                                            |
| strokeColor | Any valid color string  | `hsl(121deg,33%,34%)`  | Color of the icon stroke                                                        |
| strokeWidth | Any valid length string | `4px`                  | See [MDN](https://developer.mozilla.org/en-US/docs/Web/SVG/Content_type#Length) |

## Examples
`<Boots bg='white' fg='rgb(32,134,55)'/>`

`<Xylophone bg='rgba(0,0,0,0.1)' fg='hsl(233deg,85%,20%)' strokeWidth='1rem' strokeColor='rgba(0,0,0,0.33)'/>`

`<WindTurbine bg='black' fg='black' strokeWidth='4px' strokeColor='white'/>`