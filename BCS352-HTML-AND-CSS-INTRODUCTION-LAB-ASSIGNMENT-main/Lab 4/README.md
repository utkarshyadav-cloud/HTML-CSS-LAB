STANDARD LAB PRACTICAL EXPERIMENT FORMAT

EXPERIMENT NO. 4

1. Experiment Title: Divs, Attributes and a Small Fix

2. Aim:

To group parts of a page using div elements, add a data attribute, and fix errors in a broken HTML page.

3. Software / Tools Required:

Visual Studio Code, Chrome Browser

4. Theory:

The div tag is a container used to group HTML content into sections.

The class attribute is used to identify and group elements for styling.

The id attribute provides a unique identifier for an HTML element.

The data-* attributes are used to store custom information in HTML elements. They are not directly visible on the webpage.

HTML errors such as missing closing tags or incorrect document structure can affect the proper display of a webpage. These errors must be corrected to ensure valid HTML.

5. Algorithm / Procedure:

1. Create a folder named Assignment 4.
2. Open the folder in Visual Studio Code.
3. Create a file named layout.html.
4. Add three div elements with the classes header, main, and footer.
5. Create a file named attributes.html.
6. Add a div element with id="profile".
7. Add a paragraph with data-topic="hobbies".
8. Create a file named attendance-fixed.html.
9. Correct the broken attendance HTML code.
10. Add the Attendance Report heading and student attendance details.
11. Save all files.
12. Open all files in Chrome Browser.
13. Observe the output and take screenshots.

6. Program / Queries / Commands:

layout.html:

<!-- Name: Utkarsh Yadav | Student ID: BCS2025381 | Ass: 4 -->

<div class="header">Header Section</div>
<div class="main">Main Content</div>
<div class="footer">Footer Section</div>

attributes.html:

<div id="profile">
    <p data-topic="hobbies">My hobbies are reading and coding.</p>
</div>

attendance-fixed.html:

<!DOCTYPE html>
<html>
<head>
    <title>Attendance</title>
</head>
<body>
    <h1>Attendance Report</h1>
    <p>Asha: 92%</p>
    <p>Rohan: 85%</p>
</body>
</html>

7. Input:

File names: layout.html, attributes.html, attendance-fixed.html.

The HTML files contain div elements, class and ID attributes, a custom data attribute, and attendance details.

8. Output:

layout.html: Displays Header Section, Main Content, and Footer Section.

attributes.html: Displays the paragraph containing the hobbies information.

attendance-fixed.html: Displays the Attendance Report heading and attendance percentages of Asha and Rohan.

Screenshots of all three outputs are attached.

9. Result:

Successfully implemented div elements, class and ID attributes, custom data attributes, and corrected the broken HTML attendance page.