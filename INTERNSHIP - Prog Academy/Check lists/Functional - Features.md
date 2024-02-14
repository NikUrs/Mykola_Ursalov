



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
  <td colspan="2">!!!!!!!!!!!1.2. Sending an invalid invite code</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.3. Sending empty field</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">!!!!!1.4. Sending a valid invite code in CamelCase</td>
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
  <td colspan="2">1.7. Replace an uppercase letter with a lowercase letter and vice versa</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.8. Use an expired invite code</td>
  <td>Passed</td>
  <td><a href="https://docs.google.com/spreadsheets/d/1Fn7lGfk7Sxg4w7P8sfubcdUS0Z6yhLiAXcfR8-r9ZE4/edit#gid=0"">Bug report 02 [Closed]</a></td>
</tr>
<tr>
  <td colspan="2">1.9. Validation error message</td>
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
  <td><a href="https://docs.google.com/spreadsheets/d/1N_7oR7md5W4-cm_o_eM-f7l1znAkgDw-XhvdIkCfEE0/edit#gid=0">Bug report 04 [Closed]</a></td>
</tr>
<tr>
  <td colspan="2">2.2. Sending the registration form with one empty required field</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.3. Using combinations of valid and invalid values for registration form's fields</td>
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
  <td><a href="https://docs.google.com/spreadsheets/d/1tNagMIF4eYjgD_BL5_GjFs7X_ddDJYSbpO9NZRbFwHs/edit?usp=drive_link">Bug report 005</a>, <a href="https://docs.google.com/spreadsheets/d/1tNagMIF4eYjgD_BL5_GjFs7X_ddDJYSbpO9NZRbFwHs/edit?usp=drive_link">Bug report 005</a></td>
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
  <td colspan="2">&nbsp;&nbsp;&nbsp;&nbsp;2.4.5. Using only one space for each field</td>
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
  <td colspan="2">2.5. Checked reCaptcha</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.6. Unchecked reCaptcha</td>
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
  <td colspan="2">2.14. Registration in a browser Incognito mode</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.15. Check a limit on 5 registrations for one unique invite code</td>
  <td>Passed</td>
  <td></td>
</tr>




<tr>
  <td colspan="2"><h3>3. "Success" page</h3></td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2">3.1. Opening the "Success" page using the direct link</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">3.2. Opening the "Success" page using a link from the success message</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">3.3. Follow the link "Join a Telegram bot"</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">3.4. Compare links (from the success message and on the “Success” page)</td>
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
  <td colspan="2">4.2. Generate more than one certificate</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.3. Deleting all the links of generated certificates</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.4. More than one request of generating a certificate at one time</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.5. Check a certificate’s unique number</td>
  <td>Not Run</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.6. Validation of the "Name" field (invalid type of data)</td>
  <td>Not Run</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.7. Validation of the "Course" field (invalid type of data)</td>
  <td>Not Run</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.8. Spaces before and after entered value in the "Name" and "Course" fields</td>
  <td>Not Run</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.9. Entering lowercase value in the "Name" and "Course" fields</td>
  <td>Not Run</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.10. Entering uppercase value in the "Name" and "Course" fields</td>
  <td>Not Run</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.11. Check the format of a generated certificate file</td>
  <td>Passed</td>
  <td></td>
</tr>

</table>

