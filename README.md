# Checkers
<!DOCTYPE html>
<html>
<head>
    <title>Moving Heart</title>

    <style>
        body {
            text-align: center;
            background: pink;
            font-family: Arial;
            padding-top: 100px;
        }

        #heart {
            font-size: 80px;
            cursor: pointer;
            animation: move 2s infinite alternate;
        }

        @keyframes move {
            from {
                transform: translateX(-100px);
            }
            to {
                transform: translateX(100px);
            }
        }

        button {
            padding: 10px 20px;
            font-size: 18px;
            cursor: pointer;
        }
    </style>
</head>

<body>

    <h1>My Moving Heart ❤️</h1>

    <div id="heart">❤️</div>

    <button onclick="changeHeart()">Click Me!</button>

    <p id="message"></p>

    <script>
        function changeHeart() {
            document.getElementById("message").innerHTML =
                "You clicked the heart! ❤️";
        }
    </script>

</body>
</html>
