# HNG-13-PROFILE-CARD

<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile Card</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="profile-card">
        <div class="profile-image">
            <img src="profile.jpg" alt="Profile Image">
        </div>
        <div class="profile-info">
            <h2 id="name">DOMINION ODOZI</h2>
            <p id="position">Front-end Developer</p>
            <p id="bio">Coding is my art, and web development is my canvas.</p>
         <section class="hobbies">
                <h3>Hobbies</h3>
                <ul data-testid="test-user-hobbies">
                    <li>Reading</li>
                    <li>Coding</li>
                    <li>Gaming</li>
                </ul>
            </section>
            <section class="dislikes">
                <h3>Dislikes</h3>
                <ul data-testid="test-user-dislikes">
                    <li>procastination</li>
                    <li>Early Mornings</li>
                    <li>Traffic</li>
                </ul>
            </section>
            
            <button id="follow-btn">Follow</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>

style.css
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
}

.profile-card {
    width: 300px;
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    margin: 50px auto;
    padding: 20px;
    text-align: center;
}

.profile-image {
    width: 100px;
    height: 100px;
    border-radius: 50%;
    overflow: hidden;
    margin: 0 auto;
}

.profile-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.profile-info {
    margin-top: 20px;
}

#follow-btn {
    background-color: #4CAF50;
    color: #fff;
    border: none;
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
}

#follow-btn:hover {
    background-color: #3e8e41;
}
```