# my-audio-page.<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Audio Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      text-align: center;
      padding: 50px;
    }
    h1 {
      color: #333;
    }
    audio {
      margin-top: 20px;
      width: 300px;
    }
  </style>
</head>
<body>
  <h1>Welcome to My Audio Page 🎧</h1>
  <p>Click play to listen:</p>
  <audio controls>
    <source src="song.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>
</body>
</html>
