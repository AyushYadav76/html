# html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign In Page</title>
    <link rel="stylesheet" href="signin.css">
</head>
<body>
    <div class="container">
        <form id="signInForm" onsubmit="validateForm(); return false;">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>

            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>

            <button type="submit"><a href="newlogin.html">signIn</a></button>
        </form>

        <p>Don't have an account? <a href="account.html" target="_self" >Create New Account</a></p>
    </div>

    <script src="signin.js"></script>
</body>
</html>
