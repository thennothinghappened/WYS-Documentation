The following is a template structure of how a wiki page should be layed out, using a builtin gamemaker function for example.
If information is not yet known, such as argument names being undecided or their types not yet known, please leave a message at the top of the file indicating this, like so:
# TODO: argument 1 type, argument 2 desc.

*note, following is copied from the gamemaker manual.*
## draw_text(x, y, string)

|Arg|Type|Description|
|:--|---|:--|
|x|Real|The x coordinate of the drawn string.|
|y|Real|The y coordinate of the drawn string.|
|string|String|The string to draw.|

### Returns: N/A
### Example:
```
draw_text(x, y, "Hello, " + global.Name + "!\nI hope you are well!");
```
The above code will draw a string at the instance x/y position, which will use the string stored in the global variable "Name" and split it over two lines.