<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Social Hub</title>
    <style>
        body {
            background: black url('https://img.freepik.com/free-photo/halloween-mask-decorative-rag_23-2147685548.jpg?t=st=1740433664~exp=1740437264~hmac=6305af175a98cfb2caea026ab41f41cc3270c2f3e51c439b3ffbaa26d40f547f&w=740') no-repeat center center/cover;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            margin: 0;
        }
        .container {
            text-align: center;
            padding: 20px;
            width: 100%;
            max-width: 400px; /* Limit max width for larger screens */
        }
        .button {
            display: block;
            width: 100%;
            padding: 15px;
            margin: 15px 0;
            font-size: 24px;
            text-align: center;
            color: white;
            background: rgba(255, 255, 255, 0.1);
            border: 2px solid white;
            border-radius: 10px;
            text-decoration: none;
            transition: 0.3s;
        }
        .button:hover {
            background: white;
            color: black;
        }

        /* Mobile Responsive Styles */
        @media (max-width: 600px) {
            .button {
                font-size: 18px;
                padding: 12px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <a href="https://discord.gg/guxpqE5p" class="button">Join My Discord</a>
        <a href="https://steamcommunity.com/profiles/76561198821538520/" class="button">Visit My Steam</a>
        <a href="https://www.tiktok.com/@eddy07311" class="button">Follow on TikTok</a>
        <a href="https://kick.com/eddy0731" class="button">Watch Me on Kick</a>
    </div>
</body>
</html>
