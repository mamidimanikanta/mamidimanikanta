<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix-like Homepage</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background-color: #141414;
            color: #fff;
        }

        header {
            background-color: #111;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            z-index: 1000;
        }

        header img {
            width: 100px;
            margin-left: 20px;
        }

        main {
            padding-top: 60px;
        }

        .hero {
            position: relative;
            height: 80vh;
            background: url('https://placekitten.com/1920/1080') center/cover no-repeat;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #fff;
        }

        .hero h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }

        .btn {
            display: inline-block;
            padding: 10px 20px;
            font-size: 1.2em;
            background-color: #e50914;
            color: #fff;
            text-decoration: none;
            border-radius: 3px;
            transition: background-color 0.3s ease;
        }

        .btn:hover {
            background-color: #ff0a16;
        }

        .categories {
            padding: 40px 20px;
            text-align: center;
        }

        .category {
            margin: 0 10px;
            cursor: pointer;
            transition: transform 0.3s ease;
        }

        .category:hover {
            transform: scale(1.1);
        }

        .category img {
            width: 100%;
            border-radius: 5px;
        }

        footer {
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>

    <header>
        <img src="https://www.freepnglogos.com/uploads/netflix-logo-0.png" alt="Netflix Logo">
    </header>

    <main>

        <div class="hero">
            <h1>Welcome to Netflix</h1>
            <p>Unlimited movies, TV shows, and more. Watch anywhere. Cancel anytime.</p>
            <a href="#" class="btn">Watch Now</a>
        </div>

        <div class="categories">
            <div class="category">
                <img src="https://placekitten.com/300/450" alt="Category 1">
            </div>
            <div class="category">
                <img src="https://placekitten.com/301/450" alt="Category 2">
            </div>
            <div class="category">
                <img src="https://placekitten.com/302/450" alt="Category 3">
            </div>
            <div class="category">
                <img src="https://placekitten.com/303/450" alt="Category 4">
            </div>
        </div>

    </main>

    <footer>
        <p>&copy; 2023 Netflix Clone</p>
    </footer>

</body>
</html>
