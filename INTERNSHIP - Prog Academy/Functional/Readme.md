<h3>Functional testing</h3>

- <strong>[Features](#Features)</strong>
  	- [Checklist](#Checklist)
- <strong>[API testing](#API)</strong>
- <strong>[Chatbot command testing](#Chatbot)</strong>
<hr>
<a name="Features"></a><h3>Features</h3>

<a name="Checklist"></a><h4>Check list</h4>

1. "Invite" page<br>
- sending a valid invite code<br>
- sending an invalid invite code<br>
	- sending empty field<br>
	- sending a valid invite code in CamelCase<br>
	- invite code with a space<br>
	- inappropriate data types<br>
	- replace an uppercase letter with a lowercase letter and vice versa<br>
	- use an expired invite code<br>
- validation error message<br>

2. “Registration” page<br>
- sending the registration form with valid values<br>
- sending the registration form with one empty required field<br>
- using the combination of valid and invalid values for registration form's fields<br>
- using invalid values for each field<br>
	- empty field<br>
	- inappropriate data types for each field<br>
	- the first letter is lowercase for “Name” fields<br>
	- the first letter is lowercase for the “Surname” fields<br>
	- using a space inside fields’ values<br>
	- amount of digits in phone number less than 8 and more than 16<br>
	- special characters inside a phone number (for exampe: -().)<br>
	- email address without @ character<br>
	- email address without dot<br>
	- email address without domain name<br>
	- email address without username<br>
	- email address with special characters (except -_)<br>
	- email address with numbers in domain name<br>
- checked reCaptcha<br>
- unchecked reCaptcha<br>
- using one unique invite code more than 5 times<br>
- opening the page using direct link<br>
- phone number reuse during one iteration of using one invitation code<br>
- email address reuse during one iteration of using one invitation code<br>
- validation error message for each field<br>
- follow a direct link without using invite code before<br>
- if a network is disconnected while the registration form is being sent<br>
- registration in incognito mode of a browser<br>

3. “Success” page<br>
- opening the page using the direct link<br>
- check if email with the link was sent<br>
- follow the link<br>
- compare links (from email address and on the “Success” page)<br>

4. “Certificate” page<br>
- generate the certificate <br>
- check a generated certificate’s name<br>
- check the format of generated certificate<br>
- using of invalid values<br>

<h4>Test-cases</h4>

- "Registration" page<br>
	- <a target="_blank" href="https://docs.google.com/spreadsheets/d/1k1Ho59dMCFbFvGevWtq7IEgSbBQ7ae9TdQ2aKOYOh6w/edit?usp=drive_link" target="_blank">Entering valid data in the "Email" field</a><br>
	- <a href="https://docs.google.com/spreadsheets/d/1hnf9GQcA1bh_rulY5DjwS9RoPrIlOp5Z/edit?usp=drive_link&ouid=102064553302234595178&rtpof=true&sd=true">Entering the invalid data in the "Email" field</a><br>

<h4>Bug-reports</h4>
- "Invite" page<br>
- "Registration" page<br>
- <a href="https://docs.google.com/spreadsheets/d/1tNagMIF4eYjgD_BL5_GjFs7X_ddDJYSbpO9NZRbFwHs/edit?usp=drive_link">The invalid symbols characters are shown after typing in the "Name" field without any validation error message.</a><br>
- <a href="https://docs.google.com/spreadsheets/d/1N_7oR7md5W4-cm_o_eM-f7l1znAkgDw-XhvdIkCfEE0/edit#gid=0">The valid data is shown in the "Email" field with the validation error message.</a><br>
- <a href="https://docs.google.com/spreadsheets/d/1RLyIneYOWRytbx3LyRzOx9SPPTmG_Q41-LPbeXGAhew/edit?usp=drive_link">The success page is shown after sending the  registration form with the reused email address.</a><br>
- <a href="https://docs.google.com/spreadsheets/d/1K18xAxBUOHqcjI4q2lWE5ApOid_nMb4KOtb_z22IVS0/edit?usp=drive_link">After clicking on the "Surname" label the "Fist name" field is got the focus state.</a><br>
- <a href="https://docs.google.com/spreadsheets/d/1faetb7STSzvGPd4tw0xcwHl1DdQNnbaJaeedGQMnYMM/edit?usp=drive_link">After sending the filled form with an unavailable network connection, the status code 500 is shown when this network connection is restored.</a><br>
- <a href="https://docs.google.com/spreadsheets/d/1N_7oR7md5W4-cm_o_eM-f7l1znAkgDw-XhvdIkCfEE0/edit?usp=drive_link">The valid data is shown in the "Email" field with the validation error message.</a><br>
- "Success" page<br>
- <a href="https://docs.google.com/spreadsheets/d/1lEdpjmBqe1bI956ex78mkJ58upFuzl-j71OrpFXDtts/edit#gid=0">Bug report 18. The validation error message isn’t shown after opening the “Success” page via the direct link.</a>


<hr>
<a name="API"></a><h3>API testing</h3>
<h4>Check list</h4>

1. “Invite” page<br>
- sending a valid invite code<br>
- sending an invalid invite code<br>
- sending empty field<br>
- sending a valid invite code in CamelCase<br>
- invite code with a space<br>
- inappropriate data types<br>
- successfully validation message (and status code)<br>
- validation error message (and status code)<br><br>

2. “Registration” page<br>
- sending the registration form with valid values<br>
- sending the registration form with one empty required field<br>
- using one unique invite code more than 5 times<br>
- using invalid values for each field:<br>
	- empty field<br>
	- inappropriate data types for each field<br>
	- the first letter is lowercase for “Name” fields<br>
	- the first letter is lowercase for the “Surname” fields<br>
	- using a space inside fields’ values<br>
	- amount of digits in phone numbers less than 8 and more than 16<br>
	- email address without @ character<br>
	- email address without dot<br>
	- email address without domain name<br>
	- email address without username<br>
- successfully validation message (and status code)<br>
- validation error message (and status code)<br>

3. “Success” page<br>
- links (on the page, in an email) are compared to each other<br>
- check response fields<br>
- successfully validation message (and status code)<br>
- validation error message (and status code)<br>

4. “Certificate” page<br>
- getting the unique certificate by its identifier  <br>
- check response fields<br>
- invalid data: <br>
- id is an integer but doesn’t exist<br>
- id is a character<br>
- letter<br>
- empty value<br>
- successfully validation message <br>
- validation error message if certificate not found<br>


<h4><strong>Test case</strong></h4>
- <a href="https://docs.google.com/spreadsheets/d/1NYSdLCJyl7ICzIMEK1sHL3pvW-ngJJg5/edit?usp=drive_link&ouid=102064553302234595178&rtpof=true&sd=true">Sending request with an invalid data for the name key</a><br>
- <a href="https://docs.google.com/spreadsheets/d/1tgD6m_swB5_1FQYxG0KPlwJqbFE853OK/edit?usp=drive_link&ouid=102064553302234595178&rtpof=true&sd=true">Request with an invalid value for the "invite code" key</a><br>

<h4><strong>Bug reports</strong></h4>
- <a href="https://docs.google.com/spreadsheets/d/1yyTTQz5-Sj18Bj5u6iT-W3JxO7q80B_doJE2B71GNdA/edit?usp=drive_link">JSON data in the response body isn't matched with the technical task after sending the argument with an invalid value for the "name" key.</a><br>
- Bug report 09 - [cURL]. <a href="">JSON data in the response body isn't matched with the technical task after sending the argument with an invalid value for the "name" key.</a><br>
- <a href="https://docs.google.com/spreadsheets/d/1naco2jsyGZx9750tzzymmdFa2raWN0kwfsmNIvClzOY/edit?usp=drive_link">JSON data in the response body isn't matched with the technical task after sending invalid data in the "inviteCode" key.</a><br>
- <a href="https://docs.google.com/spreadsheets/d/1GUh7iq5HOQi4Y1UEAvH2Tiz7EjniMKI_TgmAdWLBZxA/edit#gid=0">JSON data in the response body isn't matched with the technical task after when one invite code is used more than 5 times.</a>


<hr>

<a name="Chatbot"></a><h3>Chatbot commands testing</h3>

<h4>Check list</h4>

1- /set_phone<br>
	- send one valid phone number<br>
		- phone number with amount of digits on the range 9-15<br>
		- with "+" character in the start<br>
		- with 00 number in the start<br>
		- with 0 in the start<br>
		- without "+" in the start<br>
	- send one invalid phone number<br>
		- phone number with 8 and 16 digits<br>
		- phone number with special characters: ()-<br>
		- using Latin, Cyrillic alphabet<br>
		- phone number with a space inside<br>
	- send more than one phone number (positive scenario)<br>
		- send two phone numbers, that are separeted by a comma<br>
		- send three phone numbers, that are separeted by a comma<br>
	- send more than one phone number (negative scenario)	<br>
		- send one valid and one invalid phone numbers<br>
		- send two phone numbers, that are separeted by a space<br>
		- send two phone numbers with different combinations of format <br>

2- /set_email<br>
	- send valid email address<br>
	- email address with numbers in username part<br>
	- email address with -_ characters in the username part<br>
	- send invalid email address<br>
		- email address without @ character<br>
		- email address without dot in the domain name part<br>
		- email address without domain name part<br>
		- email address without username<br>
		- email address with special characters (except _ and - characters) <br>
		- email address with numbers in domain name part	<br>
		- email address with CamelCase<br>
		- email address with a space inside<br>
		- email address with one of the follow characters in the start: @.-_  <br>

3- /group_list<br>
	- check the existing groups<br>
	- check a group which was created in current “session” <br>
	- check the successfully message<br>
	- check the error message <br>

4- /invite_group_new<br>
	- send a valid data<br>
	- check a received invite link	<br>
	- send an invalid data (inappropriate data types)<br>

5- /help<br>
	- check the list of commands<br>
	- launching of each command from the list<br>

6- /broadcast<br>
	- check a message transfer with a valid data<br>
	- check a message transfer with an invalid data<br>

7- /group_new<br>
	- ввод валидного значения (позитивный сценарий)<br>
	- ввод невалидных значений<br>

8- /user_find<br>
	- send a valid id<br>
	- send an invalid id<br>
		- if user's id was removed<br>
		- use inappropriate data types<br>

9- /certificate<br>
	- send valid existing id of generated certificate<br>
	- send invalid id of generated certificate<br>
		- id number that doesn’t exist<br>
		- inappropriate data types<br>
		- id is empty	 <br>

10- /users_list<br>
	- check the existing list of users<br>
	- checking the created group during one "session"<br>
 
<h4>Test-cases</h4>
- <a href="https://docs.google.com/spreadsheets/d/18hdKZYyNR6_YuQIqBOobO_dhKbYjztsd/edit?usp=drive_link&ouid=102064553302234595178&rtpof=true&sd=true">Check the use of "set_phone" command.</a><br>

<h4>Bug reports</h4>
- Bug report 12.<a href="https://docs.google.com/spreadsheets/d/1uOoqdZPZafw1FRrFuZ5T7Wd3EeA6_8nPSSRIfzM31yk/edit#gid=0"> The validation error message is shown with program code after sending not valid values when using the “/invite_group_new” command.</a><br>
- Bug report 13.<a href="https://docs.google.com/spreadsheets/d/1bXGWtN_nC8rS-nqif5d7xvoF2fzvuHbQT6AbdUL1oWo/edit?usp=drive_link"> The validation error message isn’t shown after sending an invalid data when using the /certificate command.</a><br>
- Bug report 14.<a href="https://docs.google.com/spreadsheets/d/1-PsMUQ-eoBH3yQ_-2lPkC6U99ULIt5nGg-VgJOunlzc/edit?usp=drive_link"> The error message is shown after sending a phone number without “plus” character.</a><br>
- Bug report 15.<a href="https://docs.google.com/spreadsheets/d/1LWxdabb_98eGmV4hBbAjI-q84lk4ksIeNQY5U4NrtlU/edit#gid=0"> The error message is shown after sending a valid phone number with 9 number when using the “set_phone” command.</a><br>
- Bug report 15.1.<a href="https://docs.google.com/spreadsheets/d/1KDmJS8DEpiPMvcadH69OBqGh5TLdhZdceNJXT9O6nr4/edit#gid=0"> The error message isn’t shown with an example of the valid format of data after sending an 8-digits phone number.</a><br>
- Bug report 16.<a href="https://docs.google.com/spreadsheets/d/18BM_tOISc-QJPvabkgWjbfXBxhfvuxom9OhnQs_52oE/edit#gid=0"> The error message isn’t shown with an example of the valid format of data after sending more than one phone number.</a><br>
- Bug report 16.1<a href="https://docs.google.com/spreadsheets/d/1pkZ4mRKTQcyhCtZA4XyRZunuFaav7PJrlcMguUsSp8w/edit#gid=0"> The error message isn’t shown with an example of the valid format of data after sending more than one phone number with different length.</a><br>
- Bug report 17.<a href="The error message isn’t shown with an example of the valid format of data after sending letters for a phone number."> The error message isn’t shown with an example of the valid format of data after sending letters for a phone number.</a>
