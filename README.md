# sync-map
Script created with Google Apps Script, attached to a Google Sheet. Pulls location from a MyMaps page and adds it to the Google Sheet page.

This script was created with a base Google Sheet with the following structure (it was originally intended to feed a *"Places to Visit"* sheet, hence the column names):

<table class="tg">
  <tr>
    <th class="tg-0qe0">1</th>
    <th class="tg-npms">A</th>
    <th class="tg-npms">B</th>
    <th class="tg-npms">C</th>
    <th class="tg-npms">D</th>
    <th class="tg-npms">E</th>
    <th class="tg-0qe0">G</th>
  </tr>
  <tr>
    <td class="tg-0qe0">2</td>
    <td class="tg-9poz">Country</td>
    <td class="tg-9poz">City</td>
    <td class="tg-9poz">Place Name</td>
    <td class="tg-9poz">Type </td>
    <td class="tg-9poz">Already Visited?</td>
    <td class="tg-0lax"></td>
  </tr>
  <tr>
    <td class="tg-0qe0">3</td>
    <td class="tg-0lax">Portugal</td>
    <td class="tg-0lax">Porto</td>
    <td class="tg-0lax">Clérigos</td>
    <td class="tg-0lax">Museum</td>
    <td class="tg-0lax">Yes/No</td>
    <td class="tg-0lax"></td>
  </tr>
</table>
 
 To attach the code to a Google Sheet, open the sheet, go to Tools -> Script Editor and paste the code :) 
