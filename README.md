# contact-form
#Create contact form using HTML.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        form {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 300px;
        }

        label {
            display: block;
            margin-bottom: 8px;
        }

        input,
        textarea,
        select {
            width: 100%;
            padding: 8px;
            margin-bottom: 16px;
            box-sizing: border-box;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        button {
            background-color: #4caf50;
            color: #fff;
            padding: 10px 15px;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
    <title>Internship Contact Form</title>
</head>
<body>
    <form action="#" method="post" id="internshipContactForm">
        <label for="name">Full Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" pattern="[0-9]{10}" required>
        <small>Format: 1234567890</small>

        <label for="university">University:</label>
        <input type="text" id="university" name="university" required>

        <label for="major">Major:</label>
        <input type="text" id="major" name="major" required>

        <label for="semester">Current Semester:</label>
        <input type="number" id="semester" name="semester" required>

        <label for="internshipType">Preferred Internship Type:</label>
        <select id="internshipType" name="internshipType" required>
            <option value="full-time">Full Time</option>
            <option value="part-time">Part Time</option>
        </select>

        <label for="internshipMode">Preferred Internship Mode:</label>
        <select id="internshipMode" name="internshipMode" required>
            <option value="online">Online</option>
            <option value="offline">Offline</option>
        </select>

        <label for="domain">Domain of Internship:</label>
        <input type="text" id="domain" name="domain" required>

        <label for="education">Student Education:</label>
        <select id="education" name="education" required>
            <option value="btech-cs">B.Tech in Computer Science</option>
            <option value="btech-it">B.Tech in Information Technology</option>
            <option value="btech-ai-ds">B.Tech in AI & DS</option>
            <option value="btech-cs-d">B.Tech in CS & D</option>
            <option value="btech-it">B.Tech in IT</option>
            <!-- Add more options based on your requirements -->
        </select>

        <label for="message">Why do you want to intern with us?</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Submit</button>
    </form>
</body>
</html>

