# dateproject2
This a date web
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dating Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }

        .container {
            max-width: 960px;
            margin: 0 auto;
            padding: 2rem;
        }

        .profile-card {
            background-color: #fff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            padding: 1.5rem;
            margin: 1rem;
            border-radius: 8px;
            text-align: center;
        }

        .profile-image {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
        }

        button {
            background-color: #4caf50;
            color: white;
            border: none;
            padding: 10px 20px;
            cursor: pointer;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Dating Website</h1>
    </header>

    <div class="container">
        <div class="profile-card">
            <img class="profile-image" src="profile.jpg" alt="Profile Picture">
            <h2>John Doe</h2>
            <p>Age: 30</p>
            <p>Interests: Travel, Reading, Cooking</p>
            <p>Description: Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
