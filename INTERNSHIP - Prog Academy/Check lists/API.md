



  Platform: PC<br>
  OS: Windows<br> 
  OS Version: 10 x64<br>
  Tester: Nikolay Ursalov<br>



<table>

<tr>
  <th colspan="2"><h3>Checking</h3></th>
  <th><h3>Status</h3></th>
  <th><h3>Bug / Comments</h3></th>
</tr>

<tr>
  <td colspan="2"><h3>1. "Invite" page</h3></td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.1. Sending a valid invite code</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.2. Sending an invalid invite code</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.3. Sending empty field</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.4. Sending a valid invite code in CamelCase</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.5. Invite code with a space</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.6. Inappropriate data types</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.7. Successfully validation message (and status code)</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.8. Validation error message (and status code)</td>
  <td>Passed</td>
  <td></td>
</tr>


<tr>
  <td colspan="2"><h3>2. "Registration" page</h3></td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.1. Sending the registration form with valid values</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.2. Sending the registration form with one empty required field</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.3. Using one unique invite code more than 5 times</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.4. Using invalid values for each field</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">&nbsp;&nbsp;&nbsp;&nbsp;2.4.1. Empty field</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">&nbsp;&nbsp;&nbsp;&nbsp;2.4.2. Inappropriate data types for each field</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">&nbsp;&nbsp;&nbsp;&nbsp;2.4.3. The first letter is lowercase for “Name” fields</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">&nbsp;&nbsp;&nbsp;&nbsp;2.4.4. The first letter is lowercase for the “Surname” fields</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">&nbsp;&nbsp;&nbsp;&nbsp;2.4.5. Using a space inside fields’ values</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">&nbsp;&nbsp;&nbsp;&nbsp;2.4.6. Amount of digits in phone number less than 8 and more than 16</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">&nbsp;&nbsp;&nbsp;&nbsp;2.4.7. Special characters inside a phone number (for exampe: -().)</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">&nbsp;&nbsp;&nbsp;&nbsp;2.4.8. Email address without @ character</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">&nbsp;&nbsp;&nbsp;&nbsp;2.4.9. Email address without dot</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">&nbsp;&nbsp;&nbsp;&nbsp;2.4.10. Email address without domain name</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">&nbsp;&nbsp;&nbsp;&nbsp;2.4.11. Email address without username</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">&nbsp;&nbsp;&nbsp;&nbsp;2.4.12. Email address with special characters (except -_)</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">&nbsp;&nbsp;&nbsp;&nbsp;2.4.13. Email address with numbers in domain name</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.5. Successfully validation message (repsonse body and status code)</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.6. Validation error message (reponse body and status code)</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.7. Using one unique invite code more than 5 times</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.8. Opening the page using direct link</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.9. Phone number reuse during one iteration of using one invitation code</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.10. Email address reuse during one iteration of using one invitation code</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.11. Validation error message for each field</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.12. Follow a direct link without using invite code before</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.13. If a network is disconnected while the registration form is being sent</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.14. Registration in an incognito mode of a browser</td>
  <td>Passed</td>
  <td></td>
</tr>


<tr>
  <td colspan="2"><h3>3. "Success" page</h3></td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2">3.1. Opening the page using the direct link</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">3.2. Opening the page using the direct link</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">3.3. Follow the link</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">3.4. Compare links (from email address and on the “Success” page)</td>
  <td>Passed</td>
  <td></td>
</tr>

<tr>
  <td colspan="2"><h3>4. “Certificate” page</h3></td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.1. Generate the certificate</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.2. Check a generated certificate’s name</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.3. Check the format of generated certificate</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.4. Using of invalid values</td>
  <td>Passed</td>
  <td></td>
</tr>


</table>
