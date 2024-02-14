
  Platform: PC<br>
  OS: Windows<br> 
  OS Version: 10 x64<br>
  Tester: Nikolay Ursalov<br>

<table>
  <tr>
    <th colspan="2"><h3>Name of the verify</h3></th>
    <th colspan="2"><h3>Description of the verify</h3></th>
    <th><h3>Status</h3></th>
    <th colspan="2"><h3>Bug link</h3></th>
  </tr>

  <tr>
    <td colspan="2"><b>Creating of a product card <br>POST /api/v1/orders<b></td>
    <td colspan="2"></td>
    <td></td>
    <td colspan="2"></td>
  </tr>
  <tr>
    <td colspan="2"></td>
    <td colspan="2">201</td>
    <td></td>
    <td colspan="2"></td>
  </tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Product card creating with main fields</td>
    <td>Passed</td>
    <td colspan="2">Ссылка на баг-репорт ссылка на баг-репорт<a href="https://docs.google.com/spreadsheets/d/1meeA4eLDlrvXyTQUmsVTSgXwGKC_EpaXH5ZwLcABQ_E/edit#gid=0">Ссылка на баг-репорт</a></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Product card creating with empty fields</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Product card fields are filled with default values</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Reusing the name of an existing product</td>
    <td>Passed</td>
    <td></td>
</tr>
      
<tr>
    <td colspan="2"></td>
    <td colspan="2">Empty JSON</td>
    <td>Passed</td>
    <td></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">Product creation date</td>
    <td>Passed</td>
    <td></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">Changing of “read-only” properties</td>
    <td>Failed</td>
    <td><a href="https://docs.google.com/spreadsheets/d/1s-HLKK0Ug2x-P5IL_dIPtLnXzWMwV52jxRlorZncO5Y/edit#gid=0">Bug report 08</a></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">“Dimensions” field has only one parameter</td>
    <td>Passed</td>
    <td></td>

</tr>


<tr>
    <td colspan="2"></td>
    <td colspan="2">Sale_price value is less than a regular_price</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Sale_price value is equal to a regular_price</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Name is more than 100 letters</td>
    <td>Failed</td>
    <td><a href="https://docs.google.com/spreadsheets/d/1ixMNOZafzP_OlzMEGBeDBFSbIhklWbzp1mwOaAp3gvA/edit#gid=0">Bug report 01</a></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Description is more than 600 letters</td>
    <td>Failed</td>
    <td><a href="https://docs.google.com/spreadsheets/d/1ifrCms__vEzXN4rIkwy7FWlK4t_Unt23hyPhRKl7FCA/edit#gid=0">Bug report 02</a></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">Sale_price value is equal to a regular_price</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">400</td>
    <td></td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Fields validation (invalid data)</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2"></td>
    <td></td>
    <td></td>
</tr>




<!-- GET 1 -->
<tr>
    <td colspan="2"><b>Retrieve and view a specific product by ID: <br>GET /wp-json/wc/v3/products/<id></id>b></td>
    <td colspan="2"></td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">200</td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting of the created product card (valid product id)</td>
    <td>Passed</td>
    <td colspan="2">Ссылка на баг-репорт ссылка на баг-репорт<a href="https://docs.google.com/spreadsheets/d/1meeA4eLDlrvXyTQUmsVTSgXwGKC_EpaXH5ZwLcABQ_E/edit#gid=0">Ссылка на баг-репорт</a></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Sending GET request twice (idempotency)</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting a product card changed by PUT request</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting a product card changed by PATCH request</td>
    <td>Passed</td>
    <td></td>
</tr>
      
<tr>
    <td colspan="2"></td>
    <td colspan="2">404</td>
    <td></td>
    <td></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting a product using invalid ID (inappropriate data type)</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting a not existing product (valid ID)</td>
    <td>Passed</td>
    <td></td>
</tr>



<!-- GET 2 -->

<tr>
    <td colspan="2"><b>Retrieve and view a list of products<br>GET <b></b>/wp-json/wc/v3/products/<b></td>
    <td colspan="2"></td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">200</td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting a list of last added 20 product cards by default</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting a list with a limited number of products (max)</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting a list with a limited number of products (min)</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Paging through results using offset (valid value)</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Sorting the list in the descending order</td>
    <td>Failed</td>
    <td><a href="https://docs.google.com/spreadsheets/d/15tmvBmUuU9rNoihVAPA1KslElut87q4vOMZQHMII6vc/edit#gid=0">Bug report 10</a></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Sorting the list in the ascending order</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Searching a product by a name (valid value)</td>
    <td>Failed</td>
    <td><a href="https://docs.google.com/spreadsheets/d/1Ei3vrJGT0UmrJw0tFUlruxH1PlV6p2rHORRS_PNmDDo/edit?usp=drive_link">Bug report 04</a></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Searching a product by a name (invalid value)</td>
    <td>Failed</td>
    <td><a href="https://docs.google.com/spreadsheets/u/1/d/1tgqQaNh3MMBijczTGqSWCfKFnYJOy3R5eCOA8oqaxPs/edit#gid=0">Bug report 4.1</a></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">Limiting results to matching a string</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Limiting results to matching a status</td>
    <td>Passed</td>
    <td></td>
</tr>  


<tr>
    <td colspan="2"></td>
    <td colspan="2">Limited by publication date - after</td>
    <td>Passed</td>
    <td><a href="https://docs.google.com/spreadsheets/d/1fDigK20YsXrnppZNbgCJRpqRkk9YxkJ3qZE1Birysvg/edit#gid=0">Bug report 11</a>
    <a href="https://docs.google.com/spreadsheets/d/1opBeCCDzeltXp4bx8wTk-Uzw8oiDyi1q4iXgHsCjBsM/edit#gid=0">Bug report 05</a>
    </td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Llimited by publication date (before)</td>
    <td>Passed</td>
    <td><a href="https://docs.google.com/spreadsheets/d/1sqTLBBhVbX6GwMfvSRu8fCYP_-se9uIHVmy6eGjr8xY/edit#gid=0">Bug report 14</a></td>
</tr>  
<tr>
    <td colspan="2"></td>
    <td colspan="2">Limited by modified date - after</td>
    <td>Passed</td>
    <td><a href="https://docs.google.com/spreadsheets/d/1pve9QYrb-ewVmUFGn3eS-hZY_f21xAtkxchchhyJlqk/edit#gid=0">Bug report 12</a></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Limited by modified_date (before)</td>
    <td>Passed</td>
    <td><a href="https://docs.google.com/spreadsheets/d/1phhwZei_KU06r2ozfVEvhWhhZ6_TWqC5jwl7SmMDFw8/edit#gid=0">Bug report 13</a></td>
</tr>  


<tr>
    <td colspan="2"></td>
    <td colspan="2">Exclude one specific product id</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Exclude more than one specific product id</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Include one specific product id</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Include more than one specific product id</td>
    <td>Passed</td>
    <td></td>
</tr>

      
<tr>
    <td colspan="2"></td>
    <td colspan="2">Sorting the list in the ascending order</td>
    <td>Passed</td>
    <td></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">Using the combination of parameters</td>
    <td>Passed</td>
    <td></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">400</td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Paging through results using offset (invalid value)</td>
    <td>Failed</td>
    <td><a href="https://docs.google.com/spreadsheets/d/1R3h1dh49l95YSWCKCDpOuw4y_7FuM9XDgff7LgVyTFM/edit#gid=0">Bug report 03</a></td>
</tr>




<tr>
    <td colspan="2"><b>Retrieve and view a specific product by ID: <br>GET /wp-json/wc/v3/products/<id></b></td>
    <td colspan="2"></td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">200</td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting of the created product card (valid product id)</td>
    <td>Passed</td>
    <td colspan="2">Ссылка на баг-репорт ссылка на баг-репорт<a href="https://docs.google.com/spreadsheets/d/1meeA4eLDlrvXyTQUmsVTSgXwGKC_EpaXH5ZwLcABQ_E/edit#gid=0">Ссылка на баг-репорт</a></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Sending GET request twice (idempotency)</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting a product card changed by PUT request</td>
    <td>Passed</td>
    <td></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Getting a product card changed by PATCH request</td>
    <td>Passed</td>
    <td></td>
</tr>




<tr>
    <td colspan="2"><b>Update a specific product by ID:</b> <br>PUT /wp-json/wc/v3/products/<id></td>
    <td colspan="2"></td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">200</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">All required fields of a product card</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">Check idempotency of a PUT request</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Updating a product card partially</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">400</td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Updating one required field of a not existing product with a valid id</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">404</td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Updating one required field of a product card with an invalid id</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>





<tr>
    <td colspan="2"><b>Update a specific product by ID: (partially)</b> <br>PATCH /wp-json/wc/v3/products/<id></td>
    <td colspan="2"></td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">200</td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Updating one required field of a product card</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Updating more than one required field of a product card</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>


      
<tr>
    <td colspan="2"></td>
    <td colspan="2">400</td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Updating one required field of a not existing product with a valid id</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">404</td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Updating a product with invalid id</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>


<tr>
    <td colspan="2"><b>Delete a specific product by ID: (partially)</b> <br>DELETE /wp-json/wc/v3/products/<id></td>
    <td colspan="2"></td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">200</td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Deleting an existing product</td>
    <td>Passed</td>
    <td colspan="2"><a href="https://docs.google.com/spreadsheets/d/16q9EpxDGkAZg9yGj_gKKl-13rVKnV9OTiEyoEwb2bPc/edit#gid=0">Bug report 9</a></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Re-delete a product</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">Deleting an existing product permanently</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Re-delete a product (deleted permanently)</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">404</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Deleting an existing product permanently</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Deleting a nonexistent product with valid id</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>

<tr>
    <td colspan="2"></td>
    <td colspan="2">410</td>
    <td></td>
    <td colspan="2"></td>
</tr>
<tr>
    <td colspan="2"></td>
    <td colspan="2">Check idempotency of a DELETE request</td>
    <td>Passed</td>
    <td colspan="2"></td>
</tr>

</table>


