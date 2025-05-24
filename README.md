# Ex.06 Book Front Cover Page Design
## Date:07-11-2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
index.html:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Book Cover Page</title>
</head>
<body>
    <div class="cover">
        <img src="book logo.jpg" alt="Logo" class="logo">
        <h1 class="book-title">The Elite Personality</h1>
        <p class="description">Better Version of Yourself</p>
        <h2 class="author">by Michael</h2>
        <button class="buy-button">Buy Now</button>
    </div>
</body>
</html>

```
Styles.css:
```
/* Resetting basic styling */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body styling with centered content */
body, html {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #f5f5f5;
    font-family: Arial, sans-serif;
}

/* Main cover container */
.cover {
    text-align: center;
    padding: 40px 20px;
    border: 3px solid #35424a;
    border-radius: 15px;
    background: linear-gradient(135deg, #6a85b6, #bac8e0);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
    width: 300px;
    color: #ffffff;
    position: relative;
}

/* Logo styling */
.logo {
    width: 80px;
    margin-bottom: 20px;
    border-radius: 50%;
    background-color: rgba(255, 255, 255, 0.8);
    padding: 5px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

/* Title styling */
.book-title {
    font-size: 26px;
    color: #2a2a2a;
    font-weight: bold;
    margin-bottom: 10px;
    text-shadow: 1px 1px 3px rgba(255, 255, 255, 0.6);
}

/* Description styling */
.description {
    font-size: 16px;
    color: #2a2a2a;
    font-style: italic;
    margin-top: 10px;
    margin-bottom: 15px;
}

/* Author name styling */
.author {
    font-size: 18px;
    color: #2a2a2a;
    font-weight: 500;
    margin-top: 20px;
}

/* Buy button styling */
.buy-button {
    margin-top: 25px;
    padding: 12px 25px;
    background-color: #28a745;
    color: #ffffff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-size: 16px

```
## OUTPUT:
![image](https://github.com/user-attachments/assets/a4d21d1b-699f-4b61-bc48-5964b3bff3a1)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
