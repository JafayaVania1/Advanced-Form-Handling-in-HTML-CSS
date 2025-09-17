# Advanced-Form-Handling-in-HTML-CSS

## Advanced-html-css-form

A professional signup/login form built using HTML and CSS, demonstrating multiple input types, dropdowns, radio buttons, textarea, file upload, and form submission. Ideal for web development practice.

## Advanced HTML Form Demo

This project showcases an advanced HTML form demonstrating multiple input types, form elements, and structure.
It is useful for beginners learning HTML forms and how to create interactive user input pages.

## Features

Text Inputs: Full Name, Email, Password
Dropdown Menu: Select country
Textarea: Short bio
Radio Buttons: Gender selection
File Upload: Upload CV (PDF only)
Submit Button: To submit the form
Basic Styling: Linked external CSS file (session15.css)

## Code Example

<form id="signupform">
    <label for="name">Full Name</label>
    <input type="text" id="name" name="name" placeholder="Enter your name">

    <label for="email">Email</label>
    <input type="text" id="email" name="email" placeholder="abc@gmail.com">

    <label for="Password">Password</label>
    <input type="text" id="Password" name="Password" placeholder="*********">

    <label for="country">Country</label>
    <select name="country" id="country">
        <option value="">----Select---</option>
        <option value="pk">Pakistan</option>
        <option value="uk">United Kingdom</option>
    </select>

    <label for="bio">Short bio:</label>
    <textarea name="bio" id="bio" rows="3" placeholder="write something"></textarea>

    <h4>Gender:</h4>
    <label for="male">Male</label>
    <input type="radio" name="Gender" id="male" value="male">
    <label for="female">Female</label>
    <input type="radio" name="Gender" id="female" value="female">

    <label for="cv">Upload CV (PDF only)</label>
    <input type="file" name="CV" id="CV" accept="application/pdf">

    <input type="submit" value="Register">
</form>
