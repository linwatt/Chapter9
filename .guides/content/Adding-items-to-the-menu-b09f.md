Items are added to the menu using the `<item>` element. Each action item is described using a separate `<item>`. The `<item>` element has a number of attributes you can use, here are some of the most common ones:

<table style="width:100%">
  <tr>
    <th>item</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>android:id</td>
    <td>Gives the item a unique ID. You need this in order to refer to the item in your activity code.
</td>
  </tr>
  <tr>
    <td>android:icon</td>
    <td>The item’s icon. This is a drawable or mipmap resource.</td>
  </tr>
  <tr>
    <td>android:title</td>
    <td>The item’s text. This may not get displayed if your item has an icon if there’s not space in the action bar for both. If the item appears in the action bar’s overflow, only the text will be displayed.
</td>
  </tr>
  <tr>
    <td>android:orderInCategory</td>
    <td>An integer value that helps Android decide the order in which items should appear in the action bar.

</td>
  </tr>
</table>