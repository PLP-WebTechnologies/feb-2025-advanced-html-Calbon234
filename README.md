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

SOLUTION

<!DOCTYPE html>

<html lang="en">
 
<head>
 
    <meta charset="UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <title>Advanced HTML5 Elements and Forms</title>
    
    <style>
    
        body {
        
            font-family: Arial, sans-serif;
            
            margin: 20px;
            
            padding: 0;
            
            text-align: center;
            
        }
        
        table {
        
            width: 80%;
            
            margin: 20px auto;
            
            border-collapse: collapse;
            
        }
        
        th, td 
        
            border: 1px solid black;
            
            padding: 10px;
            
            text-align: left;
            
        }
        
        th {
        
            background-color: #f4f4f4;
            
        }
        img {
        
            width: 300px;
            
            display: block;
            
            margin: 10px auto;
            
        }
        
        form {
        
            width: 50%;
            
            margin: auto;
            
            text-align: left;
            
        }
        
        input, select {
        
            width: 100%;
            
            padding: 8px;
            
            margin: 5px 0;
            
        }
        
        button {
        
            padding: 10px;
            
            background-color: blue;
            
            color: white;
            
            border: none;
            
            cursor: pointer;
        }
        
    </style>
    
</head>

<body>


    <!-- Header -->
    
    <header>
    
    
        <h1>Advanced HTML5 Elements and Forms</h1>
        
    </header>

    <!-- Ordered List with Roman Numerals -->
    
    <section>
    
        <h2>Ordered List with Roman Numerals</h2>
        
        <ol type="I">
        
            <li>HTML</li>
            
            <li>CSS</li>
            
            <li>JavaScript</li>
            
            <li>React</li>
            
            <li>Node.js</li>
            
        </ol>
        
    </section>
    

    <!-- External Image -->
    
    <section>
    
    
        <h2>External Image</h2>
        
        <img src="https://images.pexels.com/photos/1108099/pexels-photo-1108099.jpeg" alt="Beautiful Nature">
        
    </section>
    

    <!-- Contacts Table -->
    
    <section>
    
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
                
                <td>Nairobi, Kenya</td>
                
                <td>+254712345678</td>
                
                <td>john@doe.com</td>
                
            </tr>
            
            <tr>
            
                <td>Jane Smith</td>
                
                <td>Mombasa, Kenya</td>
                
                <td>+254798765432</td>
                
                <td>jane@karake.com</td>
                
            </tr>
            
            <tr>
            
                <td>Mike Johnson</td>
                
                <td>Kisumu, Kenya</td>
                
                <td>+254701234567</td>
                
                <td>mike@mutua.com</td>
                
            </tr>
            
            <tr>
            
                <td>Sarah Brown</td>
                
                <td>Nakuru, Kenya</td>
                
                <td>+254711223344</td>
                
                <td>sarah@edwin.com</td>
                
            </tr>
            
            <tr>
            
                <td>Chris Evans</td>
                
                <td>Eldoret, Kenya</td>
                
                <td>+254722334455</td>
                
                <td>chris@ress.com</td>
                
                
            </tr>
            
        </table>
        
        
    </section>
    

    <!-- Registration Form -->
    
    <section>
    
        <h2>Registration Form</h2>
        
        <form action="#" method="post">
        
            <label for="name">Full Name:</label>
            
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            

            <label for="email">Email:</label>
            
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            

            <label for="password">Password:</label>
            
            <input type="password" id="password" name="password" placeholder="Enter your password" required>
            

            <label for="dob">Date of Birth:</label>
            
            <input type="date" id="dob" name="dob" required>
            

            <label for="gender">Gender:</label><br>
            
            <input type="radio" id="male" name="gender" value="male" required> Male
            
            <input type="radio" id="female" name="gender" value="female" required> Female
            
            <input type="radio" id="other" name="gender" value="other" required> Other
            
            <br><br>
            

            <label for="course">Select Course:</label>
            
            <select id="course" name="course" required>
            
                <option value="">-- Choose a Course --</option>
                
                <option value="computer-science">Computer Science</option>
                
                <option value="engineering">Engineering</option>
                
                <option value="business">Business</option>
                
            </select>
            

            <label>Interests:</label><br>
            
            <input type="checkbox" name="interests" value="coding"> Coding
            
            <input type="checkbox" name="interests" value="gaming"> Gaming
            
            <input type="checkbox" name="interests" value="reading"> Reading
            
            <input type="checkbox" name="interests" value="traveling"> Traveling
            
            <br><br>
            

            <button type="submit">Register</button>
            
        </form>
        
    </section>
    

    <!-- Multimedia Section -->
    
    <section>
    
        <h2>Multimedia Elements</h2>
        
        
        <!-- Audio Element -->
        
        <h3>Sample Audio</h3>
        
        <audio controls>
        
            <source src="c:\Users\bkath\Desktop\sytyi\Murembo Kwandunda Official Video By Master Kaju Ndomeo..m4a" type="audio/mpeg">
            
            Your browser does not support the audio element.
            
        </audio>
        

        <!-- Video Element -->
        
        <h3>Sample Video</h3>
        
        <video width="400" controls>
        
            <source src="c:\Users\bkath\Desktop\sytyi\7e13cf4fcc38b9997fde52228f23ba80_1742591155595.mp4" type="video/mp4">
            
            Your browser does not support the video tag.
            
        </video>
        
    </section>
    

    <!-- Footer -->
    
    <footer>
    
        <p>&copy; bkathiwa234@gmail.com</p>
        
    </footer>
    

</body>

</html>

