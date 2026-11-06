STANDARD LAB PRACTICAL EXPERIMENT FORMAT

EXPERIMENT NO. 8

1. Experiment Title: CSS Selectors

2. Aim:

To use tag selectors, a class selector and an ID selector to change colours and backgrounds of HTML elements.

3. Software / Tools Required:

Visual Studio Code, Chrome Browser

4. Theory:

CSS (Cascading Style Sheets) is used to style HTML elements.

Tag Selector: Selects elements using their tag names. For example, p { color: blue; } applies blue colour to all paragraph elements.

Class Selector: Selects elements using a class name. It is represented by a dot (.). For example, .highlight applies styles to elements having class="highlight".

ID Selector: Selects a unique element using an ID. It is represented by a hash (#). For example, #banner applies styles to the element having id="banner".

The style tag is used to write CSS inside an HTML document.

5. Algorithm / Procedure:

1. Create a folder named Assignment 8.
2. Open the folder in Visual Studio Code.
3. Create a file named first-styles.html.
4. Add a style tag and apply blue colour to paragraph elements and red colour to heading elements.
5. Create a file named class.html.
6. Apply a class selector named highlight with a yellow background.
7. Create a file named id.html.
8. Apply an ID selector named banner with a light blue background.
9. Save all files.
10. Open all files in Chrome Browser.
11. Observe the output and take screenshots.

6. Program / Queries / Commands:

first-styles.html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>CSS Tag Selector</title>

    <style>
        p {
            color: blue;
        }

        h1 {
            color: red;
        }
    </style>
</head>
<body>
    <h1>Welcome to CSS</h1>
    <p>This paragraph is blue.</p>
    <p>CSS is used to style HTML elements.</p>
</body>
</html>

class.html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>CSS Class Selector</title>

    <style>
        .highlight {
            background-color: yellow;
        }
    </style>
</head>
<body>
    <h1>Class Selector</h1>
    <p class="highlight">This paragraph has a yellow background.</p>
    <p>This paragraph has no background colour.</p>
</body>
</html>

id.html:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>CSS ID Selector</title>

    <style>
        #banner {
            background-color: lightblue;
        }
    </style>
</head>
<body>
    <h1 id="banner">CSS ID Selector</h1>
    <p>This heading has a light blue background.</p>
</body>
</html>

7. Output:

first-styles.html: The heading appears red and paragraphs appear blue.

class.html: The highlighted paragraph has a yellow background.

id.html: The heading with ID banner has a light blue background.

Screenshots of all three outputs are attached.

8. Result:

Successfully implemented CSS tag selectors, class selectors, and ID selectors to change the colours and backgrounds of HTML elements.