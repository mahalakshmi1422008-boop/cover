# Ex.05 Book Cover Page Design
## Date:14/12/25
## AIM:
To design a book back cover page using HTML and CSS.

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
```
book.html
<html>
<head>
    <title>CoverPage</title>
    <link rel="stylesheet" type="text/css" href="cover.css">
</head>

<body>
    <div class="container">

        <h1><b>About the Book</b></h1>
        <hr>

        <p>
            This book provides a comprehensive overview of Ethical Hacking.
            It explains how security meets technology. Readers will learn the essentials,
            techniques, and importance of safe digital practices.
        </p>

        <div class="quote">
            <p>A successful hacking methodology is built on accumulated experience with diverse challenges.</p>
        </div>

        <div class="author-box">
            <img src="maha.jpg" alt="Author Photo" width="100" height="100">
            <div>
<h3>S.Mahalakshmi</h3>
                <p>
                    S.Mahalakshmi is a well-known writer, singer and artist.
                    She is doing her UG in Saveetha Engineering College.
                </p>
            </div>
        </div>

        <div class="footer">
            <span>SEC Publishers</span>
            <span class="price">Price: 699rs</span>
        </div>

    </div>
</body>
</html>

cover.css

ody {

    font-family: Arial, sans-serif;
}


.container {
    background-image: url("background cover.png");
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    width: 60%;
    margin: 40px auto;
    padding: 20px 40px;
    border-radius: 12px;
    border: 3px;
    height: 700px;
    box-shadow: 0 0 10px black;
}
.text{
    color: black;
    position: relative;
    right: 60px;
}
h3 {
    color: black;
}
h1{
    color: black;
}
.quote {
    background: rgba(144,119,202);
    border-left: 5px solid rgb(13,18,110);
    padding: 10px 20px;
    margin: 20px 0;
    font-style: italic;
    border-radius: 5px;
}
.author{
    display: flex;
    background: white;
    padding: 15px;
    border-radius: 10px;
    margin-top: 20px;
}

img{
    position: relative;
    width: 100px;
    height: 130px;
    object-fit: cover;
    margin-right: 15px;
    border-radius: 8px;

}

.footer {
    margin-top: 130px;
    background:blue;
    padding: 12px 15px;
    border-radius: 8px;
    color: white;
    display: flex;
    justify-content: space-between;
    font-weight: bold;
}

.price {
    color: yellow;
}


```

## OUTPUT:

![alt text](<Screenshot (79).png>)
## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
