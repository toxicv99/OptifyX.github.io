<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TOXIC SERVICES</title>
    <style>
        /* Allgemeines Seitenlayout */
        body {
            background-color: #0d0d0d; /* Tiefschwarz für einen professionellen Look */
            color: #00FF00; /* Giftgrün */
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vh;
        }

        /* Header */
        header {
            width: 100%;
            text-align: center;
            padding: 20px;
            background-color: #111; /* Etwas helleres Schwarz für den Header */
            position: fixed;
            top: 0;
            left: 0;
            z-index: 1000;
            display: flex;
            justify-content: center; /* Zentriert den Inhalt horizontal */
            align-items: center; /* Zentriert den Inhalt vertikal */
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
        }

        header h1 {
            font-size: 3em;
            margin: 0;
            color: #00FF00;
        }

        /* Container für Inhalt */
        .container {
            margin-top: 100px; /* Abstand für den festen Header */
            text-align: center;
            padding: 40px;
            max-width: 800px;
        }

        /* Buttons für Navigation */
        .button {
            display: inline-block;
            padding: 12px 25px;
            margin: 15px;
            border: 2px solid #00FF00;
            color: #00FF00;
            text-decoration: none;
            font-size: 1.2em;
            border-radius: 5px;
            transition: background-color 0.3s, color 0.3s;
        }

        .button:hover {
            background-color: #00FF00;
            color: black;
        }

        /* Footer-Design */
        footer {
            width: 100%;
            text-align: right;
            padding: 10px;
            font-size: 0.8em;
            color: #00FF00;
            position: fixed;
            bottom: 10px;
            right: 20px;
        }

        /* Professionellerer Button für Discord */
        .discord-button {
            background-color: #5865F2; /* Discord Blau */
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 5px;
            font-size: 1.2em;
            text-decoration: none;
            transition: background-color 0.3s;
            display: inline-block;
            margin-top: 20px;
        }

        .discord-button:hover {
            background-color: #4752C4; /* Etwas dunkler bei Hover */
        }

    </style>
</head>
<body>
    <!-- Fester Header -->
    <header>
        <h1>TOXIC SERVICES</h1>
    </header>

    <!-- Hauptinhalt -->
    <div class="container">
        <a href="#services" class="button">Services</a>
        <a href="#contact" class="button">Contact</a>
        <a href="#about" class="button">About Us</a>

        <!-- Discord Button -->
        <a href="https://discord.gg/m5evbR2rFz" target="_blank" class="discord-button">Join Our Discord</a>
    </div>
    
    <!-- Footer -->
    <footer>
        &copy; 2024 TOXIC SERVICES. All rights reserved.
    </footer>
</body>
</html>
