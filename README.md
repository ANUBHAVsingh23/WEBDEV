If you mean all the README content in one single code block, here it is:

The `framesandrules.html` file demonstrates the following `frame` values:


- `void`
- `above`
- `below`
- `hsides`
- `vsides`
- `lhs`
- `rhs`
- `box`
- `border`


Example:


```html
<table border="2" frame="box">
    <tr>
        <th>Name</th>
        <th>Course</th>
    </tr>
    <tr>
        <td>Anubhav</td>
        <td>MCA</td>
    </tr>
</table>
📏 Rules Attribute

The following rules values are demonstrated:

none
rows
cols
all
groups

Example:

<table border="2" rules="all">
    <tr>
        <th>Name</th>
        <th>Course</th>
    </tr>
    <tr>
        <td>Anubhav</td>
        <td>MCA</td>
    </tr>
</table>
📝 HTML Registration Form

The form.html file contains a student registration form.

It demonstrates:

First Name
Last Name
Email ID
Mobile Number
Gender
Date of Birth
Address
City
Pin Code
State
Country
Hobbies
Qualification
Courses Applied For
Submit button
Reset button
<fieldset>
<legend>

Example:

<form>


    <fieldset>


        <legend>
            <b><center>Registration Form</center></b>
        </legend>


        <table bgcolor="red">


            <tr>
                <td>
                    <label for="fname">First Name:</label>
                </td>


                <td>
                    <input type="text"
                           id="fname"
                           name="first_name"
                           required>
                </td>
            </tr>


            <tr>
                <td>
                    <label for="email">Email ID:</label>
                </td>


                <td>
                    <input type="email"
                           id="email"
                           name="email"
                           required>
                </td>
            </tr>


            <tr>
                <td>
                    <label>Gender:</label>
                </td>


                <td>
                    <input type="radio"
                           name="gender"
                           value="male"> Male


                    <input type="radio"
                           name="gender"
                           value="female"> Female


                    <input type="radio"
                           name="gender"
                           value="other"> Other
                </td>
            </tr>


            <tr>
                <td>
                    <label>Hobbies:</label>
                </td>


                <td>
                    <input type="checkbox"
                           name="hobbies"
                           value="drawing"> Drawing


                    <input type="checkbox"
                           name="hobbies"
                           value="singing"> Singing


                    <input type="checkbox"
                           name="hobbies"
                           value="dancing"> Dancing
                </td>
            </tr>


            <tr>
                <td></td>


                <td>
                    <input type="submit" value="Submit">
                    <input type="reset" value="Reset">
                </td>
            </tr>


        </table>


    </fieldset>


</form>
📋 HTML Lists

The day1.html file demonstrates nested unordered lists.

Topics included:

Population
Size
Growth rate
Infrastructure
Transportation
Roads
Public transport
Utilities
Water
Electricity
Culture
Arts
Festivals
Comparison with Other Cities
City A
Similarities
Differences

Example:

<h1>Our City</h1>


<ul>


    <li>
        Population


        <ul>
            <li>Size</li>
            <li>Growth rate</li>
        </ul>


    </li>


    <li>
        Infrastructure


        <ul>


            <li>
                Transportation


                <ul>
                    <li>Roads</li>
                    <li>Public transport</li>
                </ul>


            </li>


            <li>
                Utilities


                <ul>
                    <li>Water</li>
                    <li>Electricity</li>
                </ul>


            </li>


        </ul>


    </li>


    <li>
        Culture


        <ul>
            <li>Arts</li>
            <li>Festivals</li>
        </ul>
    </li>


</ul>
🎓 UMS Login Page

The umsloginpage.html file demonstrates a UMS-style login interface.

Features include:

UMS Logo
Background color
Location selection
Registration Number
Password
Dashboard selection
Verification checkbox
Login button
Forgot password link
Student Mail link

The background color used is:

<body style="background-color:#FAF2F0;">

The page also uses image files:

images/
├── logo.svg
├── ums_logo1.svg
└── mail.svg
📂 Project Structure
HTML-Practice/
│
├── day1.html
├── tables.html
├── tableexample.html
├── tableattributes.html
├── framesandrules.html
├── tabletask1.html
├── form.html
├── umsloginpage.html
│
└── images/
    ├── logo.svg
    ├── ums_logo1.svg
    └── mail.svg
🚀 How to Run

No server or additional software is required.

Step 1

Download or clone the project.

Step 2

Keep all HTML files in the same folder.

Step 3

Make sure the images folder exists if you want to run umsloginpage.html.

Step 4

Open any .html file in a web browser.

For example:

Right Click → Open With → Google Chrome
🎯 Purpose

This project is created for HTML learning and practice.

The main objectives are to understand:

Basic HTML structure
HTML tables
Table attributes
rowspan
colspan
Frames
Rules
HTML forms
Fieldsets
Legends
Input elements
Dropdown menus
Checkboxes
Radio buttons
Nested lists
Basic webpage layouts
🛠️ Technologies Used
HTML5
HTML Tables
HTML Forms
HTML Lists
Basic HTML Attributes
Inline Styling
📌 Important Note

Some attributes used in these exercises, such as:

bgcolor
background
bordercolor
bordercolorlight
bordercolordark
frame
rules

are older HTML presentation attributes.

They are included in this project primarily for HTML learning and coursework.

In modern web development, CSS is generally preferred for styling and layout.

👨‍💻 Author

Anubhav

HTML Practice Collection
