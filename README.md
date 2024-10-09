<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home - My Website</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="tamplate.css">
    
    <style>
        body {
            font-family: Arial, Helvetica, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        header {
            background: #4245e6;
            color: #fff;
            padding: 20px 0;
            text-align: center;
            position: relative;
        }

        nav {
            margin: 10px 0;
        }

        nav a {
            color: #fff;
            background-color: #3a49ed;
            padding: 10px 20px;
            margin: 5px;
            text-decoration: none;
            border: none;
            border-radius: 5px;
            display: inline-block;
            transition: background-color 0.3s;
        }

        nav a:hover {
            background-color: #2c3bdb;
        }

        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
        }

        .profile-img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            position: absolute;
            top: 10px;
            right: 20px;
            border: 3px solid #fff;
        }

        footer {
            background: #4245e6;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Portosite</h1>
        <nav>
            <a href="tamplate.html">Home</a>
            <a href="about.html">About</a>
            <a href="experience.html">Experience</a>
            <a href="contact.html">Contact</a>
        </nav>
        
        
        <img src="profile.jpeg" alt="Foto Adil Zulhidan" class="profile-img">
    </header>
    
    <div class="container">
        <h2>Home</h2>
        <p>Hello, I am Adil Zulhidan. This is a website that I built myself for my future portfolio so that I can prove that I am a web developer and in the future I will continue to develop and increase my own abilities so that I can continue to be better at building websites.</p>
    </div>

    <footer>
        <p>&copy; 2024 My Website. All rights reserved.</p>
    </footer>
</body>
</html>
