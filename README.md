<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>True Crime Chronicles</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            background-color: #0e0c0c;
            color: #e0e0e0;
            font-family: 'Times New Roman', Times, serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #1a1a1a;
            padding: 20px;
            text-align: center;
            border-bottom: 4px solid #5c2c2c;
        }
        header h1 {
            margin: 0;
            color: #e0e0e0;
            text-shadow: 2px 2px 4px #330d0d;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #2a2a2a;
            padding: 10px;
            border-bottom: 2px solid #572626;
        }
        nav a {
            color: #753232;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
        }
        nav a:hover {
            color: #7c4d4d;
        }
        .hero {
            background: url('https://e1.pxfuel.com/desktop-wallpaper/251/548/desktop-wallpaper-psycho.jpg') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: rgb(196, 146, 146);
            text-shadow: 2px 2px 4px #bd8888;
        }
        .hero h2 {
            font-size: 48px;
            text-shadow: 2px 2px 8px #292121;
            background-color: rgba(0, 0, 0, 0.5); /* Semi-transparent background for better readability */
            padding: 20px;
            border-radius: 8px;
        }
        .container {
            padding: 20px;
        }
        .featured-stories {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .story {
            background-color: #1a1a1a;
            padding: 15px;
            border-radius: 8px;
            width: calc(33.333% - 20px);
            box-sizing: border-box;
            text-decoration: none;
            color: #e0e0e0;
            border: 1px solid #a39090;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }
        .story img {
            width: 100%;
            border-radius: 8px;
        }
        .story h3 {
            margin-top: 10px;
            color: #e0e0e0;
            text-shadow: 1px 1px 4px #b30000;
        }
        .story p {
            color: #b3b3b3;
        }
        .story:hover {
            background-color: #2a2a2a;
            border-color: #000000;
            transition: background-color 0.3s, border-color 0.3s;
        }
        .sidebar {
            background-color: #1a1a1a;
            padding: 20px;
            border-radius: 8px;
            border: 1px solid #2e2929;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
        }
        .sidebar h2 {
            color: #e0e0e0;
            text-shadow: 1px 1px 4px #b30000;
        }
        .sidebar p, .sidebar a {
            color: #b3b3b3;
        }
        .sidebar input {
            width: calc(100% - 20px);
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 4px;
            background-color: #333;
            color: #e0e0e0;
        }
        .sidebar button {
            width: 100%;
            padding: 10px;
            background-color: #a52828;
            border: none;
            border-radius: 4px;
            color: #e0e0e0;
            font-weight: bold;
            cursor: pointer;
        }
        .sidebar button:hover {
            background-color: #381515;
        }
        footer {
            background-color: #2a2a2a;
            color: #e0e0e0;
            text-align: center;
            padding: 20px;
            position: fixed;
            width: 100%;
            bottom: 0;
            border-top: 2px solid #442a2a;
        }
    </style>
</head>
<body>
    <header>
        <h1>True Crime Chronicles</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#serial-killers">Serial Killers</a>
            <a href="#cold-cases">Cold Cases</a>
            <a href="#victim-stories">Victim Stories</a>
            <a href="#latest-news">Latest News</a>
        </nav>
    </header>
    <section id="home" class="hero">
        <h2>Delve into the Darkest Minds</h2>
    </section>
    <div class="container">
        <h2 id="serial-killers">Featured Stories</h2>
        <div class="featured-stories">
            <a href="dennis-rader.html" class="story">
                <img src="https://assets1.cbsnewsstatic.com/hub/i/r/2022/01/13/bcaad03c-06e6-4a91-adb3-0514a8205a89/thumbnail/620x488/a9c24b62bbf68f22e9ba52134259974c/gettyimages-52260756.jpg?v=cb1f2643a8816828741cfb3a3fb2d931" alt="Dennis Rader">
                <h3>Dennis Rader: The BTK Killer</h3>
                <p>A detailed account of the life and crimes of Dennis Rader...</p>
            </a>
            <a href="joseph-deangelo.html" class="story">
                <img src="https://nypost.com/wp-content/uploads/sites/2/2020/11/Joseph-DeAngelo-01.jpg?quality=75&strip=all" alt="Joseph DeAngelo">
                <h3>Joseph DeAngelo: The Golden State Killer</h3>
                <p>Explore the chilling story of Joseph DeAngelo and his decades-long reign of terror...</p>
            </a>
            <a href="jeffrey-dahmer.html" class="story">
                <img src="https://assets2.cbsnewsstatic.com/hub/i/r/2022/10/04/50f08dac-780b-4493-9225-bf9faed1274f/thumbnail/1200x630/025d5760b7fbf4840305c994ecd5e1da/cbsn-deadliest-serial-killers-option1.jpg?v=cb1f2643a8816828741cfb3a3fb2d931" alt="Jeffrey Dahmer">
                <h3>Jeffrey Dahmer: The Milwaukee Cannibal</h3>
                <p>Discover the shocking crimes of Jeffrey Dahmer and their aftermath...</p>
            </a>
        </div>
        <div class="sidebar">
            <h2>Newsletter Signup</h2>
            <p>Subscribe to get the latest true crime stories.</p>
            <input type="email" placeholder="your-email@example.com">
            <button>Subscribe</button>
            <h2>Follow Us</h2>
            <ul>
                <li><a href="#">Instagram</a>@MurderMysteries</li>
            </ul>
            <h2>Contact Us</h2>+212684889969
            <p>For inquiries or submissions, email us at <a href="mailto:contact@truecrimechronicles.com">imane.bouguettaya17@gmail.com</a>.</p>
            <br><br><br><br><br><br>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 True Crime Chronicles. All rights reserved.</p>
    </footer>
</body>
</html>
