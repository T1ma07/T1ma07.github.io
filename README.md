<!DOCTYPE html>
<html>
<head>
    <script src="https://telegram.org/js/telegram-web-app.js"></script>
    <script>
        function sendData() {
            Telegram.WebApp.sendData("Тест");
        }
    </script>
</head>
<body>
    <button onclick="sendData()">Send text</button>
</body>
</html>
