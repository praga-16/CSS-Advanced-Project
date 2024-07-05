# CSS-Advanced-Project
## html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dribbble Clone</title>
    <link rel="stylesheet" href="C:\Users\PRAGA\OneDrive\Desktop\New folder\index.css">
</head>
<body>
    <header>
        <nav>
            <h1>Dribbble</h1>
            <ul>
                <li><a href="#">Shots</a></li>
                <li><a href="#">Designers</a></li>
                <li><a href="#">Teams</a></li>
                <li><a href="#">Community</a></li>
                <li><a href="#">Jobs</a></li>
            </ul>
            <div class="auth">
                <a href="#">Sign up</a>
                <a href="#">Sign in</a>
            </div>
        </nav>
        <div class="header-content">
            <h2>What are you working on?</h2>
            <p>Dribbble is show and tell for designers.</p>
            <button>Learn more</button>
            <button>Sign up</button>
        </div>
    </header>
    <main>
        <section class="gallery">
            <div class="card">
                <img src="c:\Users\PRAGA\OneDrive\Desktop\porche.jpeg" alt="Design 1">
                <div class="details">
                    <h3>porche</h3>
                    <p>120M views • 83M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="c:\Users\PRAGA\OneDrive\Desktop\audi.jpeg" alt="Design 1" width="350px">
                <div class="details">
                    <h3>audi</h3>
                    <p>110M views • 92M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="c:\Users\PRAGA\OneDrive\Desktop\mustang.jpeg" alt="Design 1" width="350px">
                <div class="details">
                    <h3>mustang</h3>
                    <p>130M views • 123M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="c:\Users\PRAGA\OneDrive\Desktop\lambo.jpeg" alt="Design 1">
                <div class="details">
                    <h3>lambo</h3>
                    <p>80M views • 53M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="c:\Users\PRAGA\OneDrive\Desktop\rolls.jpeg" alt="Design 1">
                <div class="details">
                    <h3>rolls</h3>
                    <p>130M views • 121M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="c:\Users\PRAGA\OneDrive\Desktop\benz.jpeg" alt="Design 1">
                <div class="details">
                    <h3>benz</h3>
                    <p>130M views • 124M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="c:\Users\PRAGA\OneDrive\Desktop\ferari.jpeg" alt="Design 1">
                <div class="details">
                    <h3>ferari</h3>
                    <p>110M views • 102M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="c:\Users\PRAGA\OneDrive\Desktop\bmw.jpeg" alt="Design 1">
                <div class="details">
                    <h3>bmw</h3>
                    <p>860M views • 832M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="c:\Users\PRAGA\OneDrive\Desktop\bugatti.jpeg" alt="Design 1">
                <div class="details">
                    <h3>bugatti</h3>
                    <p>930M views • 910M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="c:\Users\PRAGA\OneDrive\Desktop\volks.jpeg" alt="Design 1">
                <div class="details">
                    <h3>volks</h3>
                    <p>700M views • 689M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="c:\Users\PRAGA\OneDrive\Desktop\sw.jpeg" alt="Design 1">
                <div class="details">
                    <h3>swift</h3>
                    <p>450M views • 434M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="c:\Users\PRAGA\OneDrive\Desktop\hundai.jpeg" alt="Design 1">
                <div class="details">
                    <h3>hundai</h3>
                    <p>60M views • 54M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="c:\Users\PRAGA\OneDrive\Desktop\bently.jpeg" alt="Design 1">
                <div class="details">
                    <h3>bently</h3>
                    <p>140M views • 138M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="c:\Users\PRAGA\OneDrive\Desktop\bently.jpeg" alt="Design 1">
                <div class="details">
                    <h3>bently</h3>
                    <p>145M views • 139M likes</p>
                </div>
            </div>
            <div class="card">
                <img src="c:\Users\PRAGA\OneDrive\Desktop\vintage.jpeg" alt="Design 1">
                <div class="details">
                    <h3>vintage</h3>
                    <p>330M views • 312M likes</p>
                </div>
            </div>
        </section>
    </main>
</body>
</html>
```
## css
```
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #615e5e;
    color: #ffffff;
    padding: 15px;
    text-align: center;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav h1 {
    margin: 0;
    font-family: Serif;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.auth a {
    margin: 20px 10px;
    color: white;
    text-decoration: none;
}

.header-content {
    padding: 50px;
}

.header-content h2 {
    margin: 0;
}

.header-content button {
    margin: 10px;
    padding: 10px 20px;
    border: none;
    background-color: #ff4081;
    color: white;
    cursor: pointer;
}

.gallery {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
    gap: 20px;
    padding: 20px;
}

.card {
    background: white;
    border: 1px solid #ddd;
    border-radius: 5px;
    overflow: hidden;
    text-align: center;
}

.card img {
    max-width: 100%;
    display: block;
}

.card .details {
    padding: 15px;
}

.card h3 {
    margin: 10px 0;
}

.card p {
    margin: 0;
    color: #888;
}
```
## output:

![Screenshot 2024-07-05 143532](https://github.com/praga-16/CSS-Advanced-Project/assets/95266924/78ed1670-8aa5-48ea-8acd-e6b0c3856684)
