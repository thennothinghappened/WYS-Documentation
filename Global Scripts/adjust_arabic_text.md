### TODO: Better explanation needed & Use real arabic example.

## adjust_arabic_text(string)

|Arg|Type|Description|
|:--|---|:--|
|string|String|The string to adjust.|

### Returns: String
### Example:
```gml
var adjusted_text = adjust_arabic_text(" arabic text here! ");
```
The above code will change the string depending on whether it contains certain arabic characters. This function is called in `loca_adjust_for_font()` and `import_method_arabic()`.