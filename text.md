# Text Fixes

The following are snippets for fixing certain text items.

This snippet solution is for superscript items. The first one should work across all browsers, the second is a straight forward with MSO fixes.

```
sup {
  font-size:66%;
  line-height:1;
  vertical-align:top;
  mso-text-raise: 30%;
}
```

```
sup { line-height: 0; font-size: 75%; }

<!--[if gte mso 9]>
  <style>
    sup { font-size: 100% !important; }
  </style> 
<![endif]-->
```