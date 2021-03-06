---
title: 'name (meta object)'
attributions:
  - 'Microsoft Developer Network: [[Windows Internet Explorer API reference](http://msdn.microsoft.com/en-us/library/ie/hh828809%28v=vs.85%29.aspx) Article]'
compatibility:
  feature: 'name (meta object)'
  topic: html
notes:
  - 'Review import; Remove MS bias; Update/improve example; Update descriptions; Fix lists & compatibility info'
readiness: 'Not Ready'
tags:
  - Markup_Attributes
  - HTML
  - Needs_Summary
uri: 'html/attributes/name (meta object)'

---
<table class="wikitable">
<tr>
<th>
Applies to

</th>
<td>
 ?

</td>
</tr>
</table>
## Examples

This example adds **meta** tags to the **head** of an HTML document to display a smart edit button on the toolbar as of Internet Explorer 5. Because the **ProgID** **meta** tag is associated with the programmatic identifier of Word, the button displays the Word icon. When you click the button, Internet Explorer loads the document into Word using the specified document template.

``` html
<META NAME="ProgID" CONTENT="word.document">
<META NAME="Template" CONTENT="C:\Program Files\Microsoft Office\Office\html.dot">
```

## Notes

### Remarks

The **NAME** attribute typically is assigned one of the preceding well-defined values, but any arbitrary value can be specified. Custom tools can be developed to perform special actions on documents containing arbitrary **meta** tags. To enable the smart edit features in Microsoft Internet Explorer 5 or later, add a **meta** tag to the **head** of the document. Associate **ProgID** with the **NAME** attribute, and associate the programmatic identifier of the desired editor with the **CONTENT** attribute. If the specified editor is not installed or properly registered on the user's system, the edit button is not displayed. Consult the documentation of your editor to determine its programmatic identifier.

### Syntax

### Standards information

-   [Document Object Model (DOM) Level 1 Specification](http://go.microsoft.com/fwlink/p/?linkid=161725), Section 2.5.5
-   [HTML 4.01 Specification](http://go.microsoft.com/fwlink/p/?linkid=25320), Section 7.4.4

## See also

### Related pages

-   `meta`
