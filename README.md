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
 
# Tasks
- Create a well-structured HTML5 document.
- Ensure semantic correctness.

Happy Coding! 💻✨




<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Advanced HTML5 Elements</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    
    <!-- Ordered List with Roman Numerals -->
    <h2>Ordered List (Roman Numerals)</h2>
    <ol type="I">
        <li>Item One</li>
        <li>Item Two</li>
        <li>Item Three</li>
        <li>Item Four</li>
        <li>Item Five</li>
    </ol>

    <!-- External Image -->
    <h2>External Image</h2>
    <img src="https://images.pexels.com/photos/31139933/pexels-photo-31139933/free-photo-of-traditional-japanese-streetside-eatery-in-daylight.jpeg?auto=compress&cs=tinysrgb&w=400&lazy=load" alt="Traditional Japanese Streetside Eatery" width="500">
    
    <!-- Contacts Table -->
    <h2>Contacts Table</h2>
    <table>
        <tr>
            <th>Name</th>
            <th>Address</th>
            <th>Mobile</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>John Doe</td>
            <td>123 Main St</td>
            <td>+123456789</td>
            <td>john@example.com</td>
        </tr>
        <tr>
            <td>Jane Smith</td>
            <td>456 Elm St</td>
            <td>+987654321</td>
            <td>jane@example.com</td>
        </tr>
        <tr>
            <td>Bob Johnson</td>
            <td>789 Oak St</td>
            <td>+1122334455</td>
            <td>bob@example.com</td>
        </tr>
        <tr>
            <td>Alice Brown</td>
            <td>101 Pine St</td>
            <td>+5544332211</td>
            <td>alice@example.com</td>
        </tr>
        <tr>
            <td>Michael Lee</td>
            <td>222 Maple St</td>
            <td>+6677889900</td>
            <td>michael@example.com</td>
        </tr>
    </table>

    <!-- Registration Form -->
    <h2>Registration Form</h2>
    <form>
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" placeholder="Enter your name" required>
        <br><br>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" placeholder="Enter your email" required>
        <br><br>
        
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="Enter your password" required>
        <br><br>
        
        <label for="dob">Date of Birth:</label>
        <input type="date" id="dob" name="dob" required>
        <br><br>
        
        <!-- Dropdown -->
        <label for="country">Select Country:</label>
        <select id="country" name="country" required>
            <option value="">Choose...</option>
            <option value="USA">USA</option>
            <option value="UK">UK</option>
            <option value="Canada">Canada</option>
            <option value="Australia">Australia</option>
        </select>
        <br><br>
        
        <!-- Radio Buttons -->
        <label>Gender:</label>
        <input type="radio" id="male" name="gender" value="Male" required>
        <label for="male">Male</label>
        <input type="radio" id="female" name="gender" value="Female" required>
        <label for="female">Female</label>
        <br><br>
        
        <!-- Checkboxes -->
        <label>Interests:</label>
        <input type="checkbox" id="sports" name="interests" value="Sports">
        <label for="sports">Sports</label>
        <input type="checkbox" id="music" name="interests" value="Music">
        <label for="music">Music</label>
        <input type="checkbox" id="tech" name="interests" value="Tech">
        <label for="tech">Technology</label>
        <br><br>
        
        <!-- Submit Button -->
        <input type="submit" value="Register">
    </form>
    
</body>
</html>

