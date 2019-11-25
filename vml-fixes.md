# VML Fixes Mega Sheet

The following snippet you place after a VML to help break the issues with VML close items and tables. This should help correct it

```
<span style="display:none; font-size:0px; line-height:0px; max-height:0px; max-width:0px; opacity:0; overflow:hidden; visibility:hidden; mso-hide:all;"></span>
```

You can also drop this in as the closing VML background. This will clear the last paragraph so it doesnt have unwanted spacing.
```
<!--[if gte mso 9]>
<p style="margin:0;mso-hide:all"><o:p xmlns:o="urn:schemas-microsoft-com:office:office">&nbsp;</o:p></p>
        </v:textbox>
      </v:rect>
      <![endif]-->
```


This should also fix issues

```
border-spacing:0; 
mso-line-height-rule: exactly; 
mso-margin-bottom-alt:0; 
mso-margin-top-alt:0; 
mso-table-lspace:0pt; 
mso-table-rspace:0pt;
```