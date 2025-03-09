<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adam's Music Studio</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">
    <style>
        body {
            background-color: #000000;
            color: white;
            text-align: center;
        }
        .navbar {
            background-color: #ff0000;
            padding: 12px;
        }
        .navbar-brand {
            color: white;
            font-size: 1.5rem;
            text-decoration: none;
        }
        .image-container {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 10px;
            margin-top: 20px;
        }
        .image-container img {
            width: 500px; /* 長方形の幅 */
            height: 300px; /* 長方形の高さ */
            object-fit: cover;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <nav class="navbar">
        <div class="container-fluid">
            <a class="navbar-brand" href="#">Adam's Music Studio</a>
        </div>
    </nav>

    <div class="container my-5">
        <div class="image-container">
            <img src="adam.jpg" alt="Studio 1">
            
        </div>
        <div class="my-4">
            <h2 class="mt-3">Welcome to the home of Adam's Music Studio!</h2>
            <p>Offering music lessons and recording!</p>
        </div>
    </div>
    
    <div class="footer">
        <a href=https://youtu.be/FRg9e8ueRtM?si=BOFEkhLWPifabjmz>Watch our YouTube Video</a>
    </div>
 
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
