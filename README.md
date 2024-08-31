# LoginPage
----**index.html**-----
Created a login form that contains an email input field, a password input field, a "Remember Me" checkbox, and a submit button.
Implemented the login functionality within a script tag. When the submit button is clicked, the user is redirected to the loder.html page.
On the ('loder.html')page, a loading spinner is displayed for a few seconds, followed by a "Login Successful" message. After this message, the user is redirected back to the login page (login.html).
-----**Script Functionality**-----
The script includes an email validation function and a password eye icon toggle feature.
The eye icon is initially closed, and the password is hidden. Clicking the eye icon toggles the visibility of the password.
The password must be at least 6 characters long and may include digits, special characters, or letters.
The email validation uses the following regular expression:
Regex: /^[a-zA-Z0-9._%+-]+@[a-zA-Z0-9]+\.[a-zA-Z]{2,}$/
----**Explanation:**-----^: Ensures the start of the string,.[a-zA-Z0-9._%+-]+: Matches one or more characters that can be letters (uppercase or lowercase), digits, periods (.), underscores (_), percent signs (%), plus signs (+), or hyphens (-). This represents the local part (before the @ symbol) of an email address,@: Matches the literal @ character.
[a-zA-Z0-9]+: Matches one or more characters that are letters (uppercase or lowercase) or digits. This represents the domain name.
\.: Matches the literal dot (.) character.,[a-zA-Z]{2,}: Matches two or more letters (uppercase or lowercase) representing like com, org, etc.
$: Ensures the end of the string.
----**CSS Styling**-----
Proper styling has been applied for the icons, input fields, password field, and the submit button.
----**loder.html**-----
Created a loading spinner that appears after the login action.
The spinner is displayed for a few seconds, followed by a "Login Successful" message.
After displaying the success message, the user is redirected back to the login page.
Applied appropriate styling for the page, including the background images.

