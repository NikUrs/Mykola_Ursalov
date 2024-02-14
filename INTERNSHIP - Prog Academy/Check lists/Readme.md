Checklist include the following types:
1. API
2. Functional - Chatbot commands
3. Functional - Features
4. GUI (including Mobile UI)<br><br>


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
  <td colspan="2">1.7. Replace an uppercase letter with a lowercase letter and vice versa</td>
  <td>Passed</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">1.8. Use an expired invite code</td>
  <td>Passed</td>
  <td></td>
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
  <td colspan="2">2.1. Splash page</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">2.2. Landing page</td>
  <td>Pass</td>
  <td></td>
</tr>

<tr>
  <td colspan="2"><h3>3. Main menu</h3></td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2">3.1. Main Menu screen</td>
  <td>Failed</td>
  <td>Bug Report 005. Chinese words are shown on the main menu screen   
  <a href="https://docs.google.com/spreadsheets/d/136ptngWWdCebSHk99Pl9DWrSRwNVvRtw/edit?usp=drive_link&ouid=102543284257195464370&rtpof=true&sd=true">Link to Bug Report 005</a><br>
    Bug Report 006. The text of the button is shown beyond its borders    
  <a href="https://docs.google.com/spreadsheets/d/1E1L2WNzd9QIJbnJSeANiHoqPqQAB0Bup/edit?usp=drive_link&ouid=102543284257195464370&rtpof=true&sd=true">Link to Bug Report 006</a>
  </td>

</tr>
<tr>
  <tr>
  <td colspan="2">3.2. Settings</td>
  <td>Failed</td>
  <td>Bug Report 004. The button name is cut on both side in the "Setting" item
  <a href="https://docs.google.com/spreadsheets/d/1JtND4OXxiNjMxw6SjQKXEn2vB9zqSYrH/edit?usp=drive_link&ouid=102543284257195464370&rtpof=true&sd=true">Link to Bug Report 004</a></td>
</tr>
<tr>
  <td colspan="2">3.3. Market</td>
  <td>Blocked</td>
  <td>Need a credit card with funds</td>
</tr>
<tr>
  <td colspan="2">3.4. Creating of the user profile via authorization form</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">3.5. Creating of the user profile via social buttons</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">3.6. Showing of users’ records in the animation format</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">3.7. Social buttons of developers’ company</td>
  <td>Pass</td>
  <td></td>
</tr>

<tr>
  <td colspan="2"><h3>4. Menu before starting the mini game</h3></td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.1. Animations </td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.2. Constructor of the level</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.3. Navigation between mini games</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.4. Mini games modes</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.5. Guide-line before starting the game </td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">4.6. Guide-line after the game is finished</td>
  <td>Pass</td>
  <td></td>
</tr>

<tr>
  <td colspan="2"><h3>5. Game process</h3></td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.1. Guide-line for a first time experience</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.2. The custom format of the creating a mini game</td>
  <td>Failed</td>
  <td>Bug Report 001. The object model that creates enemies models is set up outside the game area <a href="https://docs.google.com/spreadsheets/d/1AkTl4XcBWRuirASFcQn99zarTem1yJeD/edit?usp=drive_link">Link to Bug Report 001</a></td>
</tr>

<tr>
  <td colspan="2">5.3. Gameplay flow including starting and completing the level</td>
  <td>Failed</td>
  <td>Bug Report 002. The timer of the game round isn’t stopped after the game is collapsed
  <a href="https://docs.google.com/spreadsheets/d/1MWLGoraF_eIUYwD_x6T1-P8UT2ttqVMi/edit?usp=drive_link&ouid=102543284257195464370&rtpof=true&sd=true">Link to Bug Report 002</a>
  </td>
</tr>
<tr>
  <td colspan="2">5.4. Character control </td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.5. Saving scores</td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.5.1. During the game</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.5.2. After the each mini game</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.5.3. After the relaunching of the game</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.6. Increasing the score during the game</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.7. Pause</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.8. Mini game timer</td>
  <td>Failed</td>
  <td>Bug Report 003. The timer of the game round isn’t stopped after the game is collapsed   
  <a href="https://docs.google.com/spreadsheets/d/1dYIw_f5Ee45g1lpl0jiZws-KVrvgtIQU/edit?usp=drive_link&ouid=102543284257195464370&rtpof=true&sd=true">Link to Bug Report 003</a></td>
</tr>



<tr>
  <td colspan="2">5.9. Menu options</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.10. Mini games' animation</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.11. Appearance of the main model characters</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.12. Appearance of the additional model characters (map, game objects)</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.13. Background Music and Sounds</td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.13.1. On the each stage of the game</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.13.2. Сompletely off the sound</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.13.3. Sound down</td>
  <td>Pass</td>
  <td></td>
</tr>
                                         
<tr>
  <td colspan="2">5.14. Game loading indicator</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.15. Exit</td>
  <td></td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.15.1. Via menu options</td>
  <td>Pass</td>
  <td></td>
</tr>
<tr>
  <td colspan="2">5.15.2. Via cross icon</td>
  <td>Pass</td>
  <td></td>
</tr>


</table>

