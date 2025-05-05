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

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewpoint" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="style.css">
            <title>intro to css</title>
    </head>
    <body>
        <nav>
            <input type="checkbox" id="check">
            <div class="toggle">
                <span class="top-line common"></span>
                <span class="middle-line common"></span>
                <span class="bottom-line common"></span>
            </div>
            <label class="logo">Assemblies of God Nwebiara</label>
            <ul>
                <li><a class="active" href="#">Home</a></li>
                <li><a ref="#">About</a></li>
                <li><a ref="#">Programmes</a></li>
                <li><a ref="#">Contact</a></li>
                <li><a ref="#">Sermons</a></li>
            </ul>
        </nav>
        <h2>​Assemblies of God Church Nwebiara, under the leadership of Resident Pastor Rev. Abey Baridomale, is experiencing a period marked by spiritual growth and community development. The congregation has witnessed numerous signs and wonders, reflecting a deepening of faith and engagement among its members. Additionally, the church is actively undertaking various projects aimed at enhancing its facilities and outreach programs, demonstrating a commitment to both spiritual and infrastructural advancement.</h2>
    </body>

* {
padding: 0;
margin: 0;
text-decoration: none;
list-style: none;
box-sizing: border-box;
}
body{
font-family: montserrat;
}
nav{
    background: #0082e6;
    height: 110px;
    width: 100%;
}
label.logo{
    color: white;
    font-size: 35px;
    line-height: 80px;
    padding: 0 100px;
    font-weight: bold;
}
nav ul{
float: right;
margin-right: 20px;
}
nav ul li{
    display: inline-block;
    line-height: 80px;
    margin: 5px;
}
nav ul li a{
    color: white;
    font-size: 17px;
    text-transform: uppercase;
    padding: 7px 17px;
    border-radius: 3px;

}
a.active, a:hover{
    background: #1b9bff;
    transition: 5s;
}
.checkbtn{
    font-size: 30px;
    color: white;
    float: right;
    line-height: 80px;
    margin-right: 40px;
}
.toggle{
    position: absolute;
    height: 30px;
    width: 30px;
    top: 20px;
    left: 15px;
    z-index: 1;
    cursor: pointer;
    border-radius: 2px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 3);
}
.toggle .common{
    position: absolute;
    height: 2px;
    width: 20px;
    background-color: #0082e6;
    border-radius: 50px;
    transition: 0.3s ease;

}
.toggle .top-line{
    top: 30px;
    left: 50px;
    transform: translate(-50%, -50%);
}
.toggle .middle-line{
    top: 50px;
    left: 50px;
    transform: translate(-50%, -50%)
}
.toggle .bottom-line{
    top: 70px;
    left: 50px;
    transform: translate(-50%, -50%) 
}



# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨
