<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f3f3f3;
            font-family: Arial, sans-serif;
        }
        .video-container {
            width: 800px;
            height: 600px;
            overflow: hidden;
            position: relative;
            margin: 0 auto;
        }
        .video-container::after {
            content: '';
            display: block;
            padding-top: 75%;
        }
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
        h1 {
            text-align: center;
            margin-bottom: 50px;
        }
    </style>
</head>
<body>
    <div class="content">
        <h1>The Garden of Words</h1>
        <div class="video-container">
            <iframe 
                src="https://streamta./e/LYw9wQqbqLtyOZ/" 
                frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen
                allowtransparency
                scrolling="no">
            </iframe>
        </div>
    </div>
</body>
</html>
