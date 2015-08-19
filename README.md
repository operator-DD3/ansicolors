# ansicolors
This simply is a list of shortcuts for ANSI Color Codes.

I have often found it very difficult to debug lua scripts containing ANSI Colors. This was designed to help with that.

### USAGE:
```lua
local ansicolors = require('ansicolors')

io.write(red,"Hello",blue ,", ",bgyellow, "World!",reset,"!!")
```
### Notes
To use this just print or io.write the variable name of the color you want. For example if you want green text just print(green). Or if you want a blue background just print(bgblue). Don't forget to reset via print(reset).
