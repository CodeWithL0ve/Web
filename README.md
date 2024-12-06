<DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Course Registration Form</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
        }
        header {
            background-color: #6200ea;
            color: white;
            text-align: center;
            padding: 10px 20px;
        }
        .container {
            max-width: 600px;
            margin: 30px auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        form label {
            display: block;
            margin: 10px 0 5px;
        }
        form input, form select, form textarea, form button {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 4px;
        }
        form button {
            background-color: #6200ea;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 16px;
        }
        form button:hover {
            background-color: #3700b3;
        }
    </style>
</head>
<body>
    <header>
        <h1>Course Registration</h1>
    </header>
    <div class="container">
    <h2>Register for a Course</h2>
        <form action="#" method="post">
            <!-- Personal Details -->
            <label for="name">Full Name</label>
            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
            
            <label for="email">Email Address</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            
            <label for="phone">Phone Number</label>
            <input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required>
            
            <!-- Course Details -->
            <label for="course">Select Course</label>
            <select id="course" name="course" required>
                <option value="" disabled selected>Choose a course</option>
                <option value="web-development">Web Development</option>
                <option value="data-science">Data Science</option>
                <option value="graphic-design">Graphic Design</option>
                <option value="digital-marketing">Digital Marketing</option>
            </select>
            
            <label for="message">Why are you interested in this course? (Optional)</label>
            <textarea id="message" name="message" rows="4" placeholder="Write your motivation here..."></textarea>
            
            <!-- Submit -->
            <button type="submit">Register</button>
        </form>
    </div>
