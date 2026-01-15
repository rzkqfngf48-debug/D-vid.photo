<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <title>Dávid Fotó</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #111;
            color: #eee;
        }

        header {
            background: url("https://images.unsplash.com/photo-1500530855697-b586d89ba3ee") center/cover;
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }

        header h1 {
            font-size: 60px;
            margin: 0;
        }

        header p {
            font-size: 20px;
            opacity: 0.8;
        }

        section {
            padding: 60px 10%;
        }

        h2 {
            border-bottom: 2px solid #444;
            padding-bottom: 10px;
        }

        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 15px;
            margin-top: 30px;
        }

        .gallery img {
            width: 100%;
            border-radius: 5px;
            transition: 0.3s;
        }

        .gallery img:hover {
            transform: scale(1.05);
        }

        footer {
            background: #000;
            text-align: center;
            padding: 20px;
            font-size: 14px;
            opacity: 0.6;
        }
    </style>
</head>
<body>

<header>
    <div>
        <h1>Dávid Fotó</h1>
        <p>Táj • Portré • Kreatív</p>
    </div>
</header>

<section>
    <h2>Rólam</h2>
    <p>
        Hobbi fotós vagyok, főleg tájképeket, portrékat és kreatív képeket készítek.
        Canon fényképezőgéppel dolgozom, és szeretem a természetes, őszinte pillanatokat.
    </p>
</section>

<section>
    <h2>Galéria</h2>
    <div class="gallery">
        <img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470">
        <img src="https://images.unsplash.com/photo-1494790108377-be9c29b29330">
        <img src="https://images.unsplash.com/photo-1500534314209-a26db0f5b4c9">
        <img src="https://images.unsplash.com/photo-1500534623283-312aade485b7">
        <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee">
        <im
