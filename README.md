# Task-3<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google Clone</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;400;500&display=swap" rel="stylesheet">
</head>
<body>

    <!-- Navigation (Optional) -->
    <nav>
        <a href="#">Gmail</a>
        <a href="#">Images</a>
        <div class="profile"></div>
    </nav>

    <!-- Main Section -->
    <div class="main">
        <img src="https://www.google.com/images/branding/googlelogo/1x/googlelogo_color_272x92dp.png" class="logo">

        <div class="search-box">
            <input type="text">
        </div>

        <div class="buttons">
            <button>Google Search</button>
            <button>I'm Feeling Lucky</button>
        </div>
    </div>

</body>
</html>
body {
    margin: 0;
    font-family: 'Roboto', sans-serif;
    background: #fff;
}

/* Top Navigation */
nav {
    display: flex;
    justify-content: flex-end;
    gap: 20px;
    padding: 15px 30px;
    font-size: 14px;
}

nav a {
    text-decoration: none;
    color: #333;
}

.profile {
    width: 32px;
    height: 32px;
    background: gray;
    border-radius: 50%;
}

/* Main Google Area */
.main {
    margin-top: 100px;
    text-align: center;
}

.logo {
    width: 272px;
    margin-bottom: 25px;
}

.search-box {
    width: 580px;
    margin: 0 auto;
    border: 1px solid #dcdcdc;
    border-radius: 25px;
    padding: 12px 20px;
    display: flex;
    align-items: center;
}

.search-box input {
    width: 100%;
    border: none;
    outline: none;
    font-size: 16px;
}

.buttons {
    margin-top: 30px;
}

.buttons button {
    padding: 10px 20px;
    margin: 5px;
    border: none;
    background: #f8f8f8;
    font-size: 14px;
    border-radius: 4px;
    cursor: pointer;
    border: 1px solid #f3f3f3;
}

.buttons button:hover {
    background: #f1f1f1;
}
