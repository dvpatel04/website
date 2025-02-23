<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Discover New Places</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #eef2f3;
            background-image:url("data:image/jpeg;base64,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") ;
            background-repeat:no-repeat ;
            background-attachment: fixed;
            background-size: 100% 100%;
        }
        header {
            background-color: #bce4f1;
            color: rgb(7, 6, 6);
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 36px;
        }
        nav {
            background-color: #333;
            padding: 15px;
            text-align: center;
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 10px 20px;
            margin: 0 10px;
            font-size: 18px;
        }
        nav a:hover {
            background-color: #575757;
            border-radius: 5px;
        }
        section {
            padding: 40px 20px;
        }
        .intro {
            text-align: center;
            margin-bottom: 30px;
        }
        .intro h2 {
            font-size: 28px;
            color: #000;
        }
        .intro p {
            font-size: 18px;
            color: #000;
            font-family: 'Times New Roman', Times, serif;
        }
        .cards {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .card {
            background-color: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            width: 30%;
            margin: 15px 0;
            transition: transform 0.3s;
        }
        .card:hover {
            transform: scale(1.05);
        }
        .card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }
        .card-content {
            padding: 15px;
            text-align: center;
        }
        .card h3 {
            font-size: 22px;
            margin-bottom: 10px;
            color: #010000;
        }
        .card p {
            font-size: 16px;
            color: #777;
        }
        footer {
            background-color: #696969;
            color: white;
            padding: 10px;
            text-align: center;
        }
    </style>
</head>
<body>

<header>
    <h1 style="font-family: cursive;">Discover New Places</h1>
    <p>Explore stunning destinations around the world</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#destinations">Destinations</a>
    <a href="#contact">Contact</a>
</nav>

<section id="home" class="intro">
    <h2>Welcome to Our Travel Portal</h2>
    <p>Your journey starts here! Discover amazing travel destinations, explore hidden gems, and plan your next adventure.</p>
</section>

<section id="destinations">
    <h2>Top Destinations</h2>
    <div class="cards">
        <div class="card">
            <img src="https://static.vecteezy.com/system/resources/thumbnails/012/400/885/small_2x/tropical-sunset-beach-and-sky-background-as-exotic-summer-landscape-with-beach-swing-or-hammock-and-white-sand-and-calm-sea-beach-banner-paradise-island-beach-vacation-or-summer-holiday-destination-photo.jpg" alt="Beach Getaway">
            <div class="card-content">
                <h3>Beach Getaway</h3>
                <p>Relax on pristine beaches, soak up the sun, and unwind by the ocean.</p>
            </div>
        </div>
        <div class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQpSH3_bRox2GK5lo9igXZtCn9XsuqpD5gybQ&s">
            <div class="card-content">
                <h3>Mountain Adventure</h3>
                <p>Challenge yourself with thrilling hikes and experience breathtaking views.</p>
            </div>
        </div>
        <div class="card">
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTkW81ctxVrzK8Wq54FD2DlND094tkmR7-_Ow&s" alt="City Exploration">
            <div class="card-content">
                <h3>City Exploration</h3>
                <p>Discover vibrant cultures, rich history, and unique landmarks.</p>
            </div>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Get in Touch</h2>
    <p>If you have any questions or need help planning your trip, don't hesitate to contact us!</p>
    <form action="#">
        <label for="name">Your Name:</label><br>
        <input type="text" id="name" name="name" required><br><br>
        <label for="email">Your Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>
        <textarea id="message" name="message" rows="4" cols="50" placeholder="Your Message"></textarea><br><br>
        <button type="submit">Send Message</button>
    </form>
</section>
<footer>
    <div class="Contact">
            <h4>Contact Us</h4>
            <p>Email:info@mytravelagancy.com</p>
            <p>phone:9902467845</p>
    </div>


    <p>&copy; 2025 Discover New Places. All Rights Reserved.</p>
</footer>

</body>
</html>

