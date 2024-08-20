---
type: info
custom_title: "single plot"
BookToc: false
---
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Text Over Image Example</title>
    <style>
        .container {
            position: relative;
            width: 100%;
            height: 50vh; /* Half of the viewport height */
        }
        .image {
            width: 50%;
            height: 50%;
            object-fit: cover; /* Ensures the image covers the container without distortion */
        }
        .type {
            position: absolute;
            top: 10px; /* Adjust as needed */
            left: 10px; /* Adjust as needed */
            color: yellow; /* Text color */
            font-size: 2em; /* Inherit the font size from h1 */
            font-family: Array-Regular; /* Inherit the font family from h1 */
            padding: 10px;
            box-sizing: border-box; /* Ensures padding is included in width calculation */
            margin: 0; /* Remove default margin for better positioning */
            line-height: 1.2; /* Adjust line-height to add vertical space */
        }
    </style>
</head>
    <body>
        <div class="container">
            <img src="images/reading.webp" alt="Background Image" class="image">
            <span class="type"><span>Hi there, feel free to look around.</span></span>
            <br><br>I use this website to jot down my thoughts and share my travels.

You can see what I am currently up to <a href="/posts" style="background-color: yellow; color: black; text-decoration: none;">here</a>.
    </body>
</html>