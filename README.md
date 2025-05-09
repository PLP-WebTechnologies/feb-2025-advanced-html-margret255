# Advanced HTML5 Elements and Forms

## Objectives
Implement HTML5 images, lists, tables, forms and input types.
Use form validation attributes.
Apply multimedia elements such as audio and video.

## Instructions

- Create an index.html file.
- Add an ordered list with roman numerals
- Add an external image from pexels.com
- Add a table of 5 contacts with; name, address, mobile and emails
- Add a registration form

>[!NOTE]
>  The registration form should have:
>- Name, email, password, and date fields.
>- A dropdown, radio buttons, and checkboxes.
>- Proper labels and placeholders.
>- Required fields and validation attributes.
>- Ensure proper indentation and commenting.
 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Maggie</title>
</head>
<body>
    <ol type="I">
        <li>HTML5 Basics</li>
        <li>Working with Forms</li>
        <li>Tables and Lists</li>
        <li>Multimedia Elements</li>
        <li>Form Validation</li>
    </ol>
    <img src="https://images.pexels.com/photos/1231234/pexels-photo-1231234.jpeg" alt="Scenic View from Pexels" width="600">
    <h2>My Table</h2>
    <table>
        <thead>
            <tr>
                <th>Name</th>
                <th>Address</th>
                <th>Mobile</th>
                <th>Email</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Alice Johnson</td>
                <td>123 Elm Street</td>
                <td>+1234567890</td>
                <td>alice@example.com</td>
            </tr>
            <tr>
                <td>Bob Smith</td>
                <td>456 Oak Avenue</td>
                <td>+9876543210</td>
                <td>bob@example.com</td>
            </tr>
            <tr>
                <td>Charlie Brown</td>
                <td>789 Pine Road</td>
                <td>+1122334455</td>
                <td>charlie@example.com</td>
            </tr>
            <tr>
                <td>David Wilson</td>
                <td>101 Maple Street</td>
                <td>+2233445566</td>
                <td>david@example.com</td>
            </tr>
            <tr>
                <td>Emma Stone</td>
                <td>202 Birch Lane</td>
                <td>+3344556677</td>
                <td>emma@example.com</td>
            </tr>
        </tbody>
    </table>
       <h2>Registration Form</h2>
       <form action="">
       <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your full name" required>
        <br><br>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>

        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Create a password" required minlength="6">
        <br><br>


        <label for="country">Select Country:</label>
        <select id="country" name="country" required>
            <option value="">--Choose--</option>
            <option value="USA">USA</option>
            <option value="UK">UK</option>
            <option value="Canada">Canada</option>
            <option value="Australia">Australia</option>
        </select>
        <br><br>

        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="Male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="Female">
        <label for="female">Female</label>
        <input type="radio" id="other" name="gender" value="Other">
        <label for="other">Other</label>
        <br><br>

        <label>Interests:</label>
        <input type="checkbox" id="coding" name="interests" value="Coding">
        <label for="coding">Coding</label>
        <input type="checkbox" id="reading" name="interests" value="Reading">
        <label for="reading">Reading</label>
        <input type="checkbox" id="sports" name="interests" value="Sports">
        <label for="sports">Sports</label>
        <br><br>
        <button type="submit">Register</button>
    </form>
      
     
     
    </table>
</body>
</html>




