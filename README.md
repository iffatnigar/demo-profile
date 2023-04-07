# demo-profile
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Iffat's Profile</title>
    <style>
        #first {
            border-radius: 50%;
        }

        * {
            padding: 20px 15px 15px 20px;
        }

        input[type=text],
        select {
            width: 100%;
            padding: 12px 20px;
            margin: 8px 0;
            display: inline-block;
            border: 1px solid #ccc;
            border-radius: 4px;
            box-sizing: border-box;
        }

        input[type=submit] {
            width: 100%;
            background-color: #40e090;
            color: white;
            padding: 14px 20px;
            margin: 8px 0;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        input[type=submit]:hover {
            background-color: #4dd9b6;
        }

        #div2 {
            border-radius: 15px;
            background-color: #de9bce;
            padding: 40px;
            border: solid;
        }
        #formHeading {
            background-color: black;
            color: whitesmoke;
            align-content: center;
            border-radius: 5px;
            font-style: verdana;
        }
    </style>
</head>

<body style="background-color: rgb(165, 211, 219);">
    <center>
        <br>
        <h1 style="font-size: 65px; background-color: #4dd9b6;">Welcome to my Landing Page</h1>
        <hr><br>
    </center>
    <div>
        <img id="first" align="right" src="image1.jpg" alt="" height="400" width="400">
    </div>
    <h2 style="color:#15163ee8;">My Name is "IFFAT NIGAR"</h2>
    <p align="left">If you're looking for random paragraphs, you've come to the right place. <br>
        When a random word or a random sentence isn't quite enough, the next logical step is to find a random paragraph.
        <br>
        We created the Random Paragraph Generator with you in mind. The process is quite simple. <br>
        Choose the number of random paragraphs you'd like to see and click the button. <br>
        Your chosen number of paragraphs will instantly appear.
    </p><br>
    <hr> <br>
    <h2>My Skills - </h2>
    <ul>
        <li>C++</li>
        <li>HTML</li>
        <li>JAVASCRIPT</li>
    </ul>
    <hr><br>
    <div id="div2">
        <h2 id="formHeading" align="center">Contact Me </h2>
        <form name="loginForm" method="post" action="loginServlet">
            <label for="name">Name: </label>
            <input type="text" id="name" name="name" placeholder="Your Name">

            <label for="lname">Email: </label>
            <input type="text" id="name" name="email" placeholder="Your Email">

            <input style="font-size: 150%; border: solid 1px black;" type="submit" value="Submit" />
        </form>
    </div>
    
</body>
</html>
