<!DOCTYPE html>
<html>
<head>
    <title>I Love You</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: #ffe6f2;
            font-family: Arial, sans-serif;
        }
        
        .love-text {
            font-size: 72px;
            color: #ff1493;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
            animation: heartbeat 1.5s infinite;
        }

        @keyframes heartbeat {
            0% { transform: scale(1); }
            15% { transform: scale(1.3); }
            30% { transform: scale(1); }
            45% { transform: scale(1.15); }
            60% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="love-text">I ❤️ You</div>
</body>
</html>
