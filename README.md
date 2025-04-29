# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨





#index.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking external CSS -->
</head>
<body>

    <h1 class="heading">Welcome to Juxx Photography</h1>

    <p id="intro">Are you passionate about colours. Join us... Lets Capture moments!</p>
    <div >
      <img src="https://images.pexels.com/photos/445109/pexels-photo-445109.jpeg?cs=srgb&dl=pexels-trinitykubassek-445109.jpg&fm=jpg" alt="Sample Image"  class="styled-image">
      <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQr1E35If-I2-LP6J90fC8Xl4fH_I0ykNwUb4OxLrtM1-BFvzUmqySJ9GDSC4bE15TdkYI&usqp=CAU" alt="Capture"  class="styled-image" height="15">
      <img src="https://captainfi.com/wp-content/uploads/2022/07/Pexels-free-images-6.jpg" alt="colourful trees" class="styled-image">
    </div>
    <div class="box">Passion in colour study(chronology) drives inner peace.</div>
    <div class="box">Lets capture these moments @Juxx Photography.</div>

</body>
</html>


#style.css

/* Font and body style */
body {
    font-family: 'Arial', sans-serif; /* Different font */
    background-color: #f0f0f0;
    padding: 20px;
}

/* Class selector */
.heading {
    color: darkblue;
    text-align: center;
    margin-bottom: 20px;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}

/* ID selector */
#intro {
    font-size: 16px;
    padding: 10px;
    margin: 15px 0;
    border: 2px solid #333;
    background-color: #ffffff;
}

/* Image styling */
.styled-image {
    display: block;
    height:5cm;
    width:10cm;
    margin: 20px auto;
    border: 5px solid #0dd828;
    padding: 10px;
}

/* Another class selector */
.box {
    background-color: #107de4;
    padding: 20px;
    margin: 30px 0;
    border: 1px dashed #999;
    font-family:fantasy;
}
div{
    background-color: #0aad33;
    margin: auto;
    align-items: center;
    display: flex;
    justify-content: center;
}
