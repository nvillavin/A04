<!-- 
File Name: my-first-web-page.html
Description: A simple webpage showing username, course name, course number, and section.
-->

<!DOCTYPE html>
<!-- The DOCTYPE declaration tells the browser this is an HTML5 document -->

<html lang="en">
<!-- The <html> element wraps all content on the page and sets the language to English -->

<head>
  <!-- The <head> section contains metadata, like the title and character encoding -->
  
  <meta charset="UTF-8">
  <!-- Sets the character encoding so the browser correctly displays text -->
  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <!-- Ensures the page scales correctly on all devices (mobile-friendly) -->
  
  <title>My First Web Page</title>
  <!-- The text that appears in the browser tab -->
  
  <style>
    /* The <style> section contains CSS for visual styling */
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      margin: 0;
      padding: 0;
      text-align: center;
    }

    h1 {
      color: #333;
      margin-top: 50px;
    }

    p {
      font-size: 18px;
      color: #555;
    }

    footer {
      margin-top: 60px;
      background-color: #222;
      color: white;
      padding: 15px 0;
    }
  </style>
</head>

<body>
  <!-- The <body> section holds all visible content on the webpage -->

  <h1>Welcome to My First Web Page</h1>
  <!-- A large heading for the page title -->

  <p><strong>Username:</strong> niv </p>
  <!-- Replace "yourUCID" with your actual UCID or username -->

  <p><strong>Course Name:</strong> Introduction to Web Development</p>
  <!-- Replace the course name as needed -->

  <p><strong>Course Number and Section:</strong> IS117 - Section 007</p>
  <!-- Replace with your actual course number and section -->

  <footer>
    <!-- The <footer> element appears at the bottom of the page -->
    
   &copy; 2025 Nicole Villavicencio — Due: October 14, 2025
    <!-- Displays copyright symbol, your name, and due date -->
  </footer>
</body>

</html>
