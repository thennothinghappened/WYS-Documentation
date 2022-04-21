If a TODO is required, do it like so:
### TODO: Better describe where this function is used.

*note, following is copied from the gamemaker manual.*
## draw_text(x, y, string)

|Arg|Type|Description|
|:--|---|:--|
|x|Real|The x coordinate of the drawn string.|
|y|Real|The y coordinate of the drawn string.|
|string|String|The string to draw.|

### Returns: N/A
### Example:
```gml
draw_text(x, y, "Hello, " + global.Name + "!\nI hope you are well!");
```
The above code will draw a string at the instance x/y position, which will use the string stored in the global variable "Name" and split it over two lines.