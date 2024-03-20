Testing of the client-server application that helps to automate the communication between school and students via Telegram chatbot.

<h3>Project structure</h3>
The project consists of the following parts:<br>

- "Home page"<br>
- “Invite” page<br>
- “Registration” page<br>
- “Success” page<br>
- “Certificate” page<br>
- Сhatbot in Telegram with its list of commands<br><br>

<h4>User / Admin (manager) rights</h4>

- “Invite” page
User can enter an invite code, which he got from a manager or another student. After that, he got access to the “Prog Academy” school website's feature functionality.

- “Registration” page
On this page user sends the registration form, which is filled with his personal information, to the server. After sending that form the user gets the email with the link to the chatbot “Prog Julia” in Telegram. <br>

- “Success” page
User can go to the chatbot “Prog Julia” by clicking on the button. <br>
Also, the link to the chatbot “Prog Julia” is sent to user's email address. <br>

- Chatbot commands
For managers, chatbot commands help to automate their work. <br>
Students can get the necessary information without managers' help.

<h4>Admin (manager) rights</h4>

- “Certificate” page<br>
Managers can generate a certificate of any course for one student or for one group.  <br>

<h4>A set of chatbot commands:</h4>

- /set_email: set email(s) to user<br>
- /certificate: command to generate and send certificates to students.<br>
- /invite_group_new: create an invite code to join the group of users<br>
- /help: list all commands<br>
- /group_list: list all groups<br>
- /users_list: show a list of all users<br>
- /set_phone: set phone(s) to user<br>
- /user_find: find the user by phone or e-mail<br>
- /group_new: create a new group of users<br>
- /broadcast: broadcast message to users<br>

Successfully message: "Command execution finished successfully!"<br><br>

<h3>Test Documentation</h3>
- Checklists (<a href="https://github.com/NikUrs/Mykola_Ursalov/tree/71998369242f5fcea825323abb43d0c6162e0b63/INTERNSHIP%20-%20Prog%20Academy/Check%20lists">Link</a>)<br>
- Test-cases (<a href="https://github.com/NikUrs/Mykola_Ursalov/tree/71998369242f5fcea825323abb43d0c6162e0b63/INTERNSHIP%20-%20Prog%20Academy/Test%20cases">Link</a>)<br>
- Bug-reports (<a href="https://github.com/NikUrs/Mykola_Ursalov/tree/71998369242f5fcea825323abb43d0c6162e0b63/INTERNSHIP%20-%20Prog%20Academy/Bug%20and%20improvement%20reports">Link</a>)<br><br>

SQL part <a href="https://github.com/NikUrs/Mykola_Ursalov/tree/main/INTERNSHIP%20-%20Prog%20Academy/SQL">Link</a>

<h3>Testing types</h3>
<h4><strong>Functional</strong> testing <a href="https://github.com/NikUrs/NikolayUrsalov/blob/main/INTERNSHIP%20-%20Prog%20Academy/Functional/Readme.md">click to the link</a></h4> 

- <strong>Features</strong><br>
- <strong>API</strong> testing<br>
- <strong>Chatbot commands testing</strong><br>
<h4><strong>GUI</strong> (including Mobile site version) testing <a href="https://github.com/NikUrs/NikolayUrsalov/blob/main/INTERNSHIP%20-%20Prog%20Academy/GUI/Check%20list%20%2B%20Bug%20reports.md">click to the link</a></h4>

<h4><strong>Cross Browser</strong> testing</h4>
Testing was performed in the following list of browsers:<br>

- Opera v.100.0.4815.21<br>
- Google Chrome v.114.0.5735.133<br>
- Mozilla Firefox v.116.0.2<br>
- Safari v.16.5.2<br>

<h4><strong>Security</strong> testing</h4>
1. Block user’s ip on 1 hour (improvement).<br>
2. Invite code isn't stored in Cookies.<br><br>








