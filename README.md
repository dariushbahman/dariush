<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dariush Bahman</title>
    <style>
        body {
            background-image: url('gieve.png');
            background-size: cover;
            background-attachment: fixed;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            color: white;
            text-align: center;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            backdrop-filter: blur(5px);
            background-color: rgba(0, 0, 0, 0.5);
            padding: 20px;
            border-radius: 15px;
        }
        h1, h2 {
            color: aqua;
            text-shadow: 0 0 10px rgba(0, 255, 255, 0.7);
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }
        .gallery a {
            display: block;
            text-decoration: none;
        }
        .gallery img {
            width: 300px;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3);
            cursor: pointer;
        }
        .gallery img:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0, 255, 255, 0.5);
        }
        .persian {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: 24px;
            margin-top: 20px;
            color: gold;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome Dariush Bahmani</h1>
        <h2>This page is only an example of the presentation(s) and does not have specific content.</h2>
        
        <div class="gallery">
            <a href="music.html">
                <img src="music.jpeg" alt="Music">
            </a>
            <a href="coding.html">
                <img src="code.jpeg" alt="coding & programming">
            </a>
            <a href="biology.html">
                <img src="biology.jpg" alt="Biology">
            </a>
            <a href="chemistry.html">
                <img src="chemirsty.jpg" alt="Chemistry">
            </a>
            <a href="connecting.html">
                <img src="gieve.jpg" alt="me">
            </a>
        </div>
        
        <div class="persian"></div>
    </div>
</body>
</html>
