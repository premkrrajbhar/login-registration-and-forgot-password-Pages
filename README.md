# Login, Registration and Forgot Password Forms

This repository contains a set of web pages designed for user authentication, including a login page, a registration page, and a forgot password page. The forms are styled using CSS for a modern and user-friendly interface.

## Demo screenshot

![Screenshot of Project](assets/screenshot.jpg)

## Live Demo

* You can check out the live demo of the project [here](https://premkrrajbhar.github.io/login-registration-and-forgot-password-Pages/)

## Table of Contents

1. [Overview](#overview)
2. [Technologies Used](#technologies-used)
3. [File Structure](#file-structure)
4. [Login Page](#login-page)
5. [Registration Page](#registration-page)
6. [Forgot Password Page](#forgot-password-page)
7. [CSS Styles](#css-styles) 
8. [Usage](#usage)
9. [Contributing](#contributing)
10. [Contact](#contact)

## Overview

The web pages are designed to facilitate user authentication. Each form is responsive and provides a seamless user experience across different devices. The pages utilize Font Awesome icons for better visual representation.

## Technologies Used

* **HTML** : Structure of the web pages.
* **CSS** : Styling of the web pages.
* **Font Awesome** : Icons for enhanced UI.
* **httpbin.org** : To send input of pages to check HTML form.
* **IDE** : Visual Studio Code

## File Structure

* ```/project-root```
 * ```index.html```
  * ```/css```
    * ```style.css```
  * ```/images```
    * ```background-img.jpg```
  * ```/pages```
    * ```register.html```
    * ```forgetpassword.html```
  * ```/assets```
    * ```screenshot.jpg```

## Login Page

##### File : ```index.html```

This page allows users to log into their accounts. It includes:

  * Input fields for **Username** and **Password**.
  * A "Remember Me" checkbox.
  * A link to the "Forgot Password" page.
  * A link to the "Register" page for new users.
  * Form submissions are sent to ```httpbin.org```, a simple HTTP Request & Response Service.


## Registration Page

##### File : ```pages/register.html```

This page allows new users to create an account. It includes:

  * Input fields for **Username**, **Email**, **Password**, and **Confirm Password**.
  * A checkbox to agree to the terms and conditions.
  * A link to the "Login" page for existing users.
  * Form submissions are sent to ```httpbin.org```, a simple HTTP Request & Response Service.


## Forgot Password Page

  ##### File : ```pages/forgetpassword.html```

This page allows users to reset their passwords. It includes:

  * Input field for the **Email** address.
  * A message instructing users to check their email for reset instructions.
  * A link to the "Login" page.
  * Form submissions are sent to ```httpbin.org```, a simple HTTP Request & Response Service.

## CSS Styles

##### File : ```css/style.css```

The CSS styles for the pages are defined in this file, providing a modern and clean look. Key styles include:

  * General reset for padding, margin, and box-sizing.
  * Responsive design that adapts to different screen sizes.
  * A backdrop blur effect for form containers.
  * Custom styles for input fields, buttons, and links.

## Usage 

To use the authentication forms, simply clone this repository and open the desired HTML file in a web browser. Each page can be accessed via links provided within the forms.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## Contact

For any questions or comments, please reach out to :
- Email : [premkumar224487@gmail.com](mailto:premkumar224487@gmail.com)
- Github : [premkrrajbhar](https://github.com/premkrrajbhar)
