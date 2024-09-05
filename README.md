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
        }

        /* Header */
        header {
            background-color: #111; /* Etwas helleres Schwarz für den Header */
            padding: 30px 0;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.5);
        }

        header h1 {
            font-size: 3em;
            margin: 0;
            color: #00FF00;
        }

        /* Hauptinhalt */
        .content {
            max-width: 900px;
            margin: 0 auto;
            padding: 60px 20px;
            text-align: center;
        }

        /* Button-Stil */
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

        /* Discord Button */
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

        /* Footer-Design */
        footer {
            background-color: #111;
            color: #00FF00;
            padding: 20px;
            text-align: right;
            font-size: 0.8em;
            position: fixed;
            bottom: 0;
            width: 100%;
            right: 0;
        }

        /* Container für Dienstleistungen */
        .services {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            padding: 40px 0;
        }

        .service-card {
            background-color: #1a1a1a;
            padding: 20px;
            border: 1px solid #00FF00;
            border-radius: 8px;
            width: 250px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.5);
            text-align: center;
            transition: transform 0.2s;
        }

        .service-card:hover {
            transform: scale(1.05);
        }

        .service-card h3 {
            margin-bottom: 10px;
            color: #00FF00;
        }

        .service-card p {
            color: #ddd;
            font-size: 1em;
            line-height: 1.5;
        }

    </style>
</head>
<body>
    <!-- Fester Header -->
    <header>
        <h1>TOXIC SERVICES</h1>
    </header>

    <!-- Hauptinhalt -->
    <div class="content">
        <div class="services">
            <!-- Service-Karten -->
            <div class="service-card">
                <h3>Service 1</h3>
                <p>Beschreibung von Service 1, der erklärt, was wir tun und warum wir die besten sind.</p>
            </div>
            <div class="service-card">
                <h3>Service 2</h3>
                <p>Beschreibung von Service 2, der erklärt, was wir tun und warum wir die besten sind.</p>
            </div>
            <div class="service-card">
                <h3>Service 3</h3>
                <p>Beschreibung von Service 3, der erklärt, was wir tun und warum wir die besten sind.</p>
            </div>
        </div>

        <!-- Discord Button -->
        <a href="https://discord.gg/m5evbR2rFz" target="_blank" class="discord-button">Join Our Discord</a>
    </div>

    <!-- Footer -->
    <footer>
        &copy; 2024 TOXIC SERVICES. All rights reserved.
    </footer>
</body>
</html>
