<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sikretong Malupet na para kay marco pogi lang</title>
    <link rel="icon" href="favicon.png" type="image/png"> <!-- This links to your favicon -->
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #FBBBB9;
            color: #C25A7C;
            margin: 0;
            padding: 20px;
        }
        .login, .confession {
            width: 80%;
            max-width: 500px;
            margin: 20px;
            padding: 20px;
            background-color: #FFC0CB;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
            display: none;
        }
        .login.visible {
            display: block;
        }
        .confession.visible {
            display: block;
        }
        h1 {
            margin-top: 20px;
            text-align: center;
        }
        input[type="password"], button {
            width: 100%;
            padding: 10px;
            margin-top: 10px;
            font-size: 16px;
        }
        button {
            background-color: #FFC0CB;
            color: #fff;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background-color: #FBBBB9;
        }
    </style>
</head>
<body>

<h1>Private Message</h1>

<div class="login visible">
    <h2>Lagay mo password here sis</h2>
    <input type="password" id="passwordInput" placeholder="Enter the password">
    <button onclick="checkPassword()">Unlock</button>
</div>

<div class="confession">
    <h2>Misig ko para sayo my honeybunchsugarplum</h2>
    <p id="confessionMessage">
        <!-- This is the message you want your crush to read -->
        Hi marco, jsyk, this confession is fake. HEHEHEZ GUSTO KO LANG MA TRY CUZ WHY NOTTTT?? Imma kabisado this if it works and ACTUALLY confess using this. OH AND BTW, I asked for chatGPT's help para makagawa nito hehe
    </p>
</div>

<script>
    const correctPassword = "MarcoMacalaylay123"; // Change this to your password

    function checkPassword() {
        const enteredPassword = document.getElementById('passwordInput').value;
        if (enteredPassword === correctPassword) {
            document.querySelector('.login').classList.remove('visible');
            document.querySelector('.confession').classList.add('visible');
        } else {
            alert("Incorrect password. Try again.");
        }
    }
</script>

</body>
</html>
