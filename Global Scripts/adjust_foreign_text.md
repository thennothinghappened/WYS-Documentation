### TODO: Better explanation needed & Use real arabic example.

## adjust_foreign_text(string)

|Arg|Type|Description|
|:--|---|:--|
|string|String|The string to adjust.|

### Returns: String
### Example:
```gml
var adjusted_text = adjust_foreign_text("/* arabic text here! */");
```
At initial inspection, this function seems to add spaces around text.
This function is only used in `adjust_arabic_text`.