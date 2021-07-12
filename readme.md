# Instagram

## Prerequisites
* Computer literacy
* Internet connectivity
* Users killer photos for the likes and followers
## Description
* A clone of the famous instagram application.
* The application enables the user to share and upload own pictures. The user can follow other users directly through suggestions or search for a name in particular.

## Languages used
* Python(Django3)
* html5
* javascript(j-query)
* css3(Bootstrap)
* postgress


## Behaviour Development Design
1. **login to the application**
* Input: input the details as required by the fields
* Output: User successfully logged to the application

1. **Error logging in**
* Username taken,invalid email,password mismatch or you have not registerd.

2. **Signup to the application**
* Input: input the details as required by the fields
* Output: User registered.

1. **Error signing up in the application**
* Username taken,invalid email or password mismatch.

3. **Forgot password**
* Input: Click on the forgot password link and you will be redirected to a form for password reset.
* Output: If followed correctly you will recieve a confirmation email with the details for a new password.

4. **Handling profile**
* Input: Click on the profile tab on the navbar.
* Output: Profile page where user can upload and delete profile information. i.e pictures and bios.

5. **Searching other users**
* Input: Input the name of the user on the search form on the navbar.If the searched user exist,you get a match and you can follow him/her
* Output: All available users with the searched name.
1. **Null response**
* The searched user does not exist in the database

6. **Change password or logout**
* Input: Click on the settings tab on the navbar and select your choice from the dropdown list.
* Output: Logout for logging you out and change your password for doing exactly that.


7. **Upload pictures/photos/images**
* Input: Click on the upload button and select your image of choice.
* Output:Image uploaded. The accepted formats are png, jpeg and webm.Other formats might not work.

8. **Comment and like  pictures**
* Input: Click on the uploaded image.User has to be logged in.
* Output:A comma/dark heart which turns red for a like when clicked and a textfield to write your comments.
9. **Note**
+ The site is fully responsive and will work on any device size

## Live Link
[Link]()


## License
Copyright (c) 2021 Peter Kiru

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE..

## Author
**Peter Kiru**