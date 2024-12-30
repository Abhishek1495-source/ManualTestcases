<table><tr><th colspan="1" valign="bottom">TC ID</th><th colspan="1" valign="bottom">TC MODULE /SCREEN</th><th colspan="1" valign="bottom">TEST SCENARIO</th></tr>
<tr><td colspan="1" valign="bottom">TC_01</td><td colspan="1" valign="bottom">Splash Screen</td><td colspan="1" valign="bottom">Verify that the splash screen displays correctly when the application starts</td></tr>
<tr><td colspan="1" valign="bottom">TC_02</td><td colspan="1" rowspan="4" valign="top">Login</td><td colspan="1" valign="bottom">Verify the Login screen design</td></tr>
<tr><td colspan="1" valign="bottom">TC_03</td><td colspan="1" valign="bottom">Verify the place holder in "Email"field</td></tr>
<tr><td colspan="1" valign="bottom">TC_04</td><td colspan="1" valign="bottom">Verify to cursor blink functionality</td></tr>
<tr><td colspan="1" valign="bottom">TC_05</td><td colspan="1" valign="bottom">Verify the place holder in "please enter Email"field</td></tr>
<tr><td colspan="1" valign="bottom">TC_06</td><td colspan="1" valign="bottom">Login</td><td colspan="1" valign="bottom">Verify valid username and password allow successful login.</td></tr>
<tr><td colspan="1" valign="bottom">TC_07</td><td colspan="1" valign="bottom">Login</td><td colspan="1" valign="bottom">Verify  invalid Email /incomplete shows an error message.</td></tr>
<tr><td colspan="1" valign="bottom">TC_08</td><td colspan="1" valign="bottom">Login</td><td colspan="1" valign="bottom">Verify  invalid password shows an error message.</td></tr>
<tr><td colspan="1" valign="bottom">TC_09</td><td colspan="1" valign="bottom">Login</td><td colspan="1" valign="bottom">Verify  invalid Email and password show an error message.</td></tr>
<tr><td colspan="1" valign="bottom">TC_10</td><td colspan="1" valign="bottom">Login</td><td colspan="1" valign="bottom">Verify  the login cannot proceed with an empty Email</td></tr>
<tr><td colspan="1" valign="bottom">TC_11</td><td colspan="1" valign="bottom">Login</td><td colspan="1" valign="bottom">Verify  the login cannot proceed with an empty password.</td></tr>
<tr><td colspan="1" valign="bottom">TC_12</td><td colspan="1" valign="bottom">Login</td><td colspan="1" valign="bottom">Verify the login cannot proceed with both fields empty</td></tr>
<tr><td colspan="1" valign="bottom">TC_13</td><td colspan="1" valign="bottom">Login</td><td colspan="1" valign="bottom">Verify  the password is visiable when we click on eye icon</td></tr>
<tr><td colspan="1" valign="bottom">TC_14</td><td colspan="1" valign="bottom">Login</td><td colspan="1" valign="bottom">Verify  the password is invisiable when we don't click on eye icon</td></tr>
<tr><td colspan="1" valign="bottom">TC_15</td><td colspan="1" valign="bottom">Login/forget password</td><td colspan="1" valign="bottom">Verify that the "Forget Password" link is accessible from the login page.</td></tr>
<tr><td colspan="1" valign="bottom">TC_16</td><td colspan="1" valign="bottom">Login/forget password</td><td colspan="1" valign="bottom">Verify that submitting a valid registered email address sends a password  reset link.</td></tr>
<tr><td colspan="1" valign="bottom">TC_17</td><td colspan="1" valign="bottom">Login/forget password</td><td colspan="1" valign="bottom">Verify that submitting an invalid or unregistered email address shows  an appropriate error message.</td></tr>
<tr><td colspan="1" valign="bottom">TC_18</td><td colspan="1" valign="bottom">Login/forget password</td><td colspan="1" valign="bottom">Verify that the user can successfully reset their password with a  strong, valid password.</td></tr>
<tr><td colspan="1" valign="bottom">TC_19</td><td colspan="1" valign="bottom">Login</td><td colspan="1" valign="bottom">Verify to cursor blink functionality</td></tr>
<tr><td colspan="1" valign="bottom">TC_20</td><td colspan="1" valign="bottom">Login</td><td colspan="1" rowspan="2" valign="bottom">Verify the remember me /check box functionality</td></tr>
<tr><td colspan="1" valign="bottom">TC_21</td><td colspan="1" valign="bottom">Login</td></tr>
<tr><td colspan="1" valign="bottom">TC_22</td><td colspan="1" valign="bottom">Login</td><td colspan="1" valign="bottom">Verify  to check hover visible on the login button</td></tr>
<tr><td colspan="1" valign="bottom">TC_23</td><td colspan="1" valign="bottom">Login</td><td colspan="1" valign="bottom">Verify to check handicon when we move cursor on Login button</td></tr>
<tr><td colspan="1" valign="bottom">TC_24</td><td colspan="1" valign="bottom">Login</td><td colspan="1" valign="bottom"></td></tr>
</table>


|TEST STEP|EXPECTED RESULT|ACTUAL RESULT|
| :-: | :-: | :-: |
|Launch the application.|The splash screen appears and is centered on the screen.|As per expected|
|1-Open Login screen   2-Observe the screen|Sign in screen should be as a approved design|As per expected|
|1-Open the Login screen   2-Observe the place holder field when we don't enter the Email|"Please enter email" place holder should be visible when we don't fill a email|As per expected|
|1-Open Login screen   2-Click on the place holder field|Cursor blink start should be starting point|As per expected|
|1-Open Login screen   2-Observe the place holder field 3-Enter the email|"Please enter email" place holder shouldn't be visible when we fill a email|As per expected|
|1-Open the login page. 2-Enter a valid Email  3-Enter a valid password. 4-Click the login button.|The user is redirected to the homepage/dashboard, and a  welcome message is displayed|As per expected|
|1-Open the login page. 2-Enter a invalid Email  3-Enter a valid password. 4-Click the login button.|An error message should be  displayed: "Invalid email ".|As per expected|
|1-Open the login page. 2-Enter a valid Email  3-Enter a Invalid password. 4-Click the login button.|An error message should be  displayed: "Invalid password".|As per expected|
|1-Open the login page. 2-Enter a Invalid Email  3-Enter a Invalid password. 4-Click the login button.|An error message Should be  displayed: "Invalid Email or password".|As per expected|
|1-Open the login page. 2-Leave the Email  field empty. 3-Enter a valid password. 4-Click the login button.|The form should prompt the user to enter a email  with a message like  "Email addres is required".|As per expected|
|1-Open the login page. 2-Enter a valid Email  3-Leave the password  field empty. 4-Click the login button.|The form should prompt the user to enter a password with a message like  "Password is required".|As per expected|
|1-Open the login page. 2-Leave the Email  field empty. 3-Leave the password  field empty. 4-Click the login button.|The form should prompt the user to enter both a Email and a password with  messages like "Email is required" and "Password is required|As per expected|
|1-Open the login page. 2-Enter the password 3-Click on eye icon|password should be visible on the password field|As per expected|
|1-Open the login page. 2-Enter the password|password shouldn't be visible on the password field|As per expected|
|1-Open the login page. 2-Click on the "Forget Password" link.|The user is redirected to the "Forget Password" page.|As per expected|
|1\.Open the "Forget Password" page. 2.Enter a valid registered email address 3.Click on the "Submit" button.|A success message is displayed, indicating that a password  reset link has been sent to the entered email address.|As per expected|
|1\.Open the "Forget Password" page. 2.Enter a Invalid Unregistered email address 3.Click on the "Submit" button.|An error message should be displayed, indicating that the  email address is not registered.|As per expected|
|1\.Open the password reset page via the reset link. 2.Enter a strong, valid new password 3.Confirm the new password. 4.Click on the "Reset Password" button.|A success message is displayed, indicating that the password  has been reset successfully, and the user can log in  with the new password.|As per expected|
|1\.Open the Login page  2.Click on email input field|Cursor blink start should be starting point|As per expected|
|1-Open Login screen 2-click on the remember me( checkbox)|Checkbox should appear filled|As per expected|
|1-Open Login screen 2-Don't click on the remember me( checkbox)|Checkbox shouldn't be appear filled|As per expected|
|1-Open Login screen 2-click on the Login  button|Hover should be show on Login button|As per expected|
|1-Open Login screen 2-click on the Login screen|Hand icon should be show on Login  button|As per expected|
|||As per expected|



|STATUS|COMMENTS|Bug (link)||
| :-: | :-: | - | - |
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|pass||||
|||||

