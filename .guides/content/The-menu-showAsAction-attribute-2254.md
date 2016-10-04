The `showAsAction` attribute is used to say how you want the item to appear in the action bar. As an example, you can use it to get an item to appear in the overflow rather than the main action bar, or to place an item on the main action bar only if there’s room. The attribute can take the following values:

<table style="width:100%">
  <tr>
    <th>showAsAction</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>ifRoom</td>
    <td>Place the item in the action bar if there’s space. If there’s not space, put it in the overflow.
</td>
  </tr>
  <tr>
    <td>withText</td>
    <td>Include the item’s title text.</td>
  </tr>
  <tr>
    <td>never</td>
    <td>Put the item in the overflow area, and never in the main action bar.
</td>
  </tr>
  <tr>
    <td>always</td>
    <td>Always place the item in the main area of the action bar. This value should be used sparingly; if you apply this to many items, they may overlap each other.
</td>
  </tr>
</table>