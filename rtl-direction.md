# RTL Direction Email

The following snippet is an example of the right to left direction fix for top to bottom mobile content but aligned right in other email clients.

```
<td valign="top" style="margin:0;padding:0;background:#fff;border-collapse:collapse;">
  <!--[if (gte mso 9)|(IE)]>
  <table width="600" dir="rtl">
    <tr>
      <td width="247" dir="ltr" >
        <![endif]-->
        <table align="right" class="table-text" cellpadding="0" border="0" width="247" style="margin:0;padding:0;border:0;width:247px;min-width:247px;background:#fff;border-collapse:collapse;">
          <tbody><tr>
            <td valign="top" style="margin:0;padding:0;background:#ffffff;border-collapse:collapse;"></td>
          </tr>
        </tbody></table>
        <!--[if (gte mso 9)|(IE)]>
      </td>
      <td width="353" dir="ltr" >
        <![endif]-->
        <table align="left" class="table-text" cellpadding="0" border="0" width="353" style="margin:0;padding:0;border:0;width:353px;min-width:353px;background:#ffffff;border-collapse:collapse;">
          <tbody><tr>
            <td valign="top" style="margin:0;padding:0;background:#ffffff;border-collapse:collapse;"></td>
          </tr>
        </tbody></table>
        <!--[if (gte mso 9)|(IE)]>
      </td>
    </tr>
  </table>
  <![endif]-->
</td><span style="display:none; font-size:0px; line-height:0px; max-height:0px; max-width:0px; opacity:0; overflow:hidden; visibility:hidden; mso-hide:all;"></span>
```