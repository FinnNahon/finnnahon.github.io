---
type: bookshelf
title: "bookshelf"
BookToc: false
---

# bookshelf

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Behind Text</title>
    <style>
        .background-container {
            position: relative;
            width: 100%;
            height: 900px; /* Adjust height as needed */
            background-image: url('/images/bookshelf.png');
            background-size: cover;
            background-position: center;
            color: white; /* Adjust text color as needed */
        }
        .background-container h2 {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 2em; /* Adjust font size as needed */
            margin: 0;
        }
    </style>
</head>
<body>
    <div class="background-container">
        <span style="color:red;"><h2><br><br><br><br><br><img src="/images/oranges.jpg" width="88" height="200" alt="oranges"> <img src="/images/loop.jpg" width="88" height="200" alt="oranges"></h2></span>
    </div>
</body>
</html>