<!DOCTYPE html>
<html>
<head>
  <title>My Website</title>
</head>
<body style="text-align:center; font-family:Arial;">
  <h1>Welcome</h1>
  <p>This is my first live website</p>
</body>
</html>
<img src="your-image.jpg" alt="My Photo" width="300">https://www.youtube.com/embed/VIDEO_ID<h2>My Photo</h2>
<img src="photo.jpg" alt="My Photo" width="300">body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    text-align: center;
    color: #333;
}

h2 {
    color: #0077cc;
}

img {
    border-radius: 10px;
    margin: 20px 0;
}
iframe {
    margin: 20px 0;
    border-radius: 10px;
}<meta name="viewport" content="width=device-width, initial-scale=1.0">/* Images और iframe responsive बनाना */
img, iframe {
    max-width: 100%;
    height: auto;
}

/* Text और layout responsive */
body {
    margin: 0;
    padding: 0 10px;
}

/* Small screen के लिए font और spacing adjust */
@media (max-width: 600px) {
    h2 {
        font-size: 18px;
    }
    body {
        padding: 0 5px;
    }
}
