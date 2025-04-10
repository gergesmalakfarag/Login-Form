<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Form</title>
</head>
<body>
    <h1>Login Form</h1>
    <form id="loginForm">
        <label for="username">Email:</label>
        <input type="text" id="email" name="email" placeholder="Email" required>
        <br><br>
        <label for="username">Username:</label>
        <input type="text" id="username" name="username" placeholder="username" required>
        <br><br>
        <label for="password">Password:</label>
        <input type="password" id="password" name="password" placeholder="password" required>
        <br><br>
        
        <label for="rememberMe">Remember Me:</label>
        <input type="checkbox" id="rememberMe" name="rememberMe">
        <br><br>
        <button onclick="document.location='task22.html'" type="submit">Login</button>
    </form>
    <script src="./task11.js"></script>
</body>
</html>
