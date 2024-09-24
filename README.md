ASSIGNMENT
Your Assignment: Build a Linktree!
________________________________________
Assignment Instructions 
Goal: Create a personal Linktree-style page using HTML, CSS, and Flexbox.
Learning Objectives:
1.	Understand basic HTML - Use HTML to structure your personal Linktree page.
2.	Apply CSS for Styling - Use CSS to design and style the page, focusing on layout, colors, and fonts.
3.	Implement Flexbox - Utilize Flexbox to organize content in a flexible and responsive manner.
Submission Guidelines
•	Code Quality - Ensure your HTML and CSS code is clean, well-commented, and follows best practices.
•	Responsiveness - Your page should be responsive and function well on a desktop.
•	Functionality - All links should be clickable and lead to the correct destinations.
•	Creativity - While functionality is key, adding personal flair and creativity is highly encouraged.
Submission Format: Submit a zipfile containing the project or your github link. We will be reviewing each others code in pairs.
Evaluation Criteria:
•	Code organization and readability
•	Effective use of HTML and CSS
•	Layout functionality across different devices
•	Design and aesthetic appeal
Make sure your page is fully functional and represents your personal and professional brand well! This is a great way to start establishing a place where recruiters or hiring managers can find out more about you beyond a resume!
 
Step 1: Set Up Project Structure
1.	Create a project folder.
2.	Inside the folder, create two files: index.html for the structure and styles.css for the styling.
/project-folder
    ├── index.html
    └── styles.css
Step 2: Write the Basic HTML Structure
Open index.html and add the basic HTML structure:
html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Linktree</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <header>
            <img src="your-photo.jpg" alt="Your Name" class="profile-pic">
            <h1>Your Name</h1>
            <p>Web Developer | Designer | Your Tagline</p>
        </header>

        <section class="links">
            <a href="https://your-portfolio.com" target="_blank">Portfolio</a>
            <a href="https://github.com/yourusername" target="_blank">GitHub</a>
            <a href="https://www.linkedin.com/in/yourprofile/" target="_blank">LinkedIn</a>
            <a href="mailto:youremail@gmail.com">Contact Me</a>
        </section>
    </div>
</body>
</html>
 
Step 3: CSS Styling
In styles.css, you can add the following styles for layout and design:
css
Copy code
/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
}

/* Container for all content */
.container {
    background-color: white;
    border-radius: 10px;
    padding: 20px;
    text-align: center;
    width: 90%;
    max-width: 400px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

/* Profile Picture Styling */
.profile-pic {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    margin-bottom: 10px;
}

/* Header styling */
header h1 {
    font-size: 24px;
    margin: 10px 0;
}

header p {
    font-size: 14px;
    color: #666;
}

/* Links Styling */
.links {
    display: flex;
    flex-direction: column;
    gap: 15px;
    margin-top: 20px;
}

.links a {
    background-color: #4CAF50;
    color: white;
    text-decoration: none;
    padding: 10px;
    border-radius: 5px;
    font-size: 18px;
    transition: background-color 0.3s ease;
}

.links a:hover {
    background-color: #45a049;
}

/* Responsiveness */
@media (max-width: 600px) {
    .container {
        width: 100%;
        padding: 10px;
    }
}
Step 4: Make It Responsive with Flexbox
Flexbox is already utilized in the links section by using flex-direction: column; and gap: 15px;, ensuring that the links stack on top of each other. It’s important that your layout adapts well to different screen sizes, which is handled with the media query in the CSS.
Step 5: Add Personalization
•	Replace your-photo.jpg with an actual image of yourself or a logo.
•	Customize the links in the a tags to your own portfolio, GitHub, LinkedIn, and email.
•	Tweak colors, fonts, and layout as per your personal branding.
Step 6: Test Responsiveness
•	Open the project in a browser and resize the window to see how the page responds on different screen sizes.
•	Right-click on the browser, select "Inspect", and use the device toolbar to test on mobile views.
 
Step 7: Submit Your Assignment
1.	Zip your project folder or upload it to GitHub.
2.	Submit the zip file or share the GitHub repository link.
Checklist for Submission:
•	Code is well-commented, readable, and organized.
•	Links are functional and lead to correct destinations.
•	The design is responsive on both desktop and mobile devices.
•	You've added some personal flair to the project.
This will help you create a great personal Linktree-style page and showcase your HTML, CSS, and Flexbox skills! Let me know if you need further assistance.
 
Appendix A - Here’s a step-by-step explanation of the index.html file for someone new to web development:
1. <!DOCTYPE html>
This line is called the doctype declaration. It tells the browser that the document is written in HTML5, the latest version of HTML. It ensures that the browser renders the page in standard mode.
html
Copy code
<!DOCTYPE html>
2. <html lang="en">
The <html> tag is the root element of the HTML document. Everything inside the page will be nested within this tag. The lang="en" attribute specifies that the language of the document is English.
html
Copy code
<html lang="en">
3. <head>
The <head> element contains metadata about the document, such as its title and links to external resources like CSS stylesheets. This section doesn't display content on the webpage, but it plays a vital role in structuring the page.
html
Copy code
<head>
4. <meta charset="UTF-8">
This tag defines the character encoding for the HTML document. UTF-8 is the most widely used encoding that supports almost all characters from different languages.
html
Copy code
<meta charset="UTF-8">
5. <meta name="viewport" content="width=device-width, initial-scale=1.0">
This tag makes your webpage responsive. It ensures that the page will be scaled correctly on different devices, like mobile phones or tablets. It tells the browser to adjust the page width to the screen's width.
html
Copy code
<meta name="viewport" content="width=device-width, initial-scale=1.0">
6. <title>My Linktree</title>
The <title> element defines the title of the webpage, which appears in the browser tab. In this case, it’s set to "My Linktree."
html
Copy code
<title>My Linktree</title>
7. <link rel="stylesheet" href="styles.css">
This line links the external CSS file (styles.css) to the HTML page. The CSS file is where all the styling (colors, fonts, layout) for the page is defined. Without this link, the page would just display as plain HTML without any design.
html
Copy code
<link rel="stylesheet" href="styles.css">
8. <body>
The <body> tag contains all the visible content on the webpage. Anything inside the <body> element will be displayed in the browser window.
html
Copy code
<body>
9. <div class="container">
A <div> is a container element used to group other HTML elements together. Here, we are using a <div> with the class "container" to wrap all the content of the page. Classes help to apply specific styles to the elements in CSS.
html
Copy code
<div class="container">
10. <header>
The <header> tag is a semantic HTML element that typically contains introductory content or navigation links. In this case, it contains your profile picture, name, and tagline.
html
Copy code
<header>
11. <img src="your-photo.jpg" alt="Your Name" class="profile-pic">
This is an image tag. It displays an image on the webpage.
•	src="your-photo.jpg" specifies the path to the image file.
•	alt="Your Name" provides alternate text for the image if it cannot be displayed (good for accessibility).
•	class="profile-pic" applies the CSS styles for the image.
html
Copy code
<img src="your-photo.jpg" alt="Your Name" class="profile-pic">
12. <h1>Your Name</h1>
This is an h1 heading element, which is the largest heading tag in HTML. It typically represents the main title or heading of the page, in this case, your name.
html
Copy code
<h1>Your Name</h1>
13. <p>Web Developer | Designer | Your Tagline</p>
The <p> tag defines a paragraph. Here, it contains a short tagline or description of you. This text will appear below your name.
html
Copy code
<p>Web Developer | Designer | Your Tagline</p>
14. <section class="links">
The <section> tag groups related content together. Here, the section has the class "links," and it contains a series of clickable links.
html
Copy code
<section class="links">
15. <a href="https://your-portfolio.com" target="_blank">Portfolio</a>
The <a> tag defines a hyperlink. It allows users to click and go to another webpage.
•	href="https://your-portfolio.com" is the URL where the link will send the user.
•	target="_blank" makes the link open in a new tab.
•	The text between the opening and closing <a> tags, in this case, Portfolio, is what users will click on.
Example link:
html
Copy code
<a href="https://your-portfolio.com" target="_blank">Portfolio</a>
16. Other Links
Repeat the same structure as the previous link for GitHub, LinkedIn, and email. Each link takes the user to a different destination.
html
Copy code
<a href="https://github.com/yourusername" target="_blank">GitHub</a>
<a href="https://www.linkedin.com/in/yourprofile/" target="_blank">LinkedIn</a>
<a href="mailto:youremail@gmail.com">Contact Me</a>
17. </section> and </div>
These are closing tags for the <section> and <div> elements. They indicate that the section of links and the entire content inside the "container" has ended.
html
Copy code
</section>
</div>
18. </body> and </html>
These are the closing tags for the body and HTML document. They signal the end of the HTML structure.
html
Copy code
</body>
</html>
Summary
•	The index.html file creates the structure of your page, with elements like headings (<h1>), paragraphs (<p>), and links (<a>).
•	It uses tags to group and organize content, with classes and IDs to apply styling later in styles.css.
•	This page includes clickable links that users can interact with and displays your profile photo, name, and tagline.
Let me know if you need further clarification on any section!

