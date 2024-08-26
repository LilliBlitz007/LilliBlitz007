<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meine Persönliche Webseite</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            padding: 1rem;
            background-color: #333;
        }
        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 1rem;
        }
        .section {
            margin-bottom: 2rem;
            padding: 1rem;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #4CAF50;
        }
        .day-schedule, .ideas {
            display: flex;
            flex-direction: column;
            gap: 1rem;
        }
        .day-part {
            background-color: #fafafa;
            padding: 1rem;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Willkommen auf meiner persönlichen Webseite</h1>
    </header>
    <nav>
        <a href="#about">Über mich</a>
        <a href="#projects">Projekte</a>
        <a href="#day">Mein Tagesablauf</a>
        <a href="#goals">Ziele</a>
        <a href="#ideas">Ideen</a>
    </nav>
    <div class="container">
        <section id="about" class="section">
            <h2>Über mich</h2>
            <p>Hier erzähle ich etwas über mich, meine Interessen und meine Philosophie.</p>
        </section>
        <section id="projects" class="section">
            <h2>Projekte</h2>
            <p>Hier zeige ich meine aktuellen und vergangenen Projekte.</p>
        </section>
        <section id="day" class="section">
            <h2>Mein Tagesablauf</h2>
            <div class="day-schedule">
                <div class="day-part">
                    <h3>Morning 🌔</h3>
                    <ul>
                        <li>5:45 Wecker</li>
                        <li>Aufstehen & Wasser trinken</li>
                        <li>Im Bad: Zähne putzen & Beauty-Schwamm nass machen</li>
                        <li>Wasser kochen</li>
                        <li>Essen holen</li>
                        <li>Musik leise anmachen</li>
                        <li>Skin Care</li>
                        <li>Gesicht rasieren & abwaschen</li>
                        <li>Säuren</li>
                        <li>Feuchtigkeits- & Sonnencreme</li>
                        <li>Bett machen</li>
                        <li>Anziehen</li>
                        <li>Make-up</li>
                        <li>Concealer auftragen</li>
                        <li>Vaseline</li>
                        <li>Deo</li>
                        <li>Lotion</li>
                        <li>Concealer verblenden</li>
                        <li>6:40 Wimpern</li>
                        <li>6:45 Haare machen</li>
                        <li>Tee einschenken</li>
                        <li>7:05 Los zum Bus</li>
                    </ul>
                </div>
                <div class="day-part">
                    <h3>School Breaks 🌝</h3>
                    <ul>
                        <li>Klasse/Sozis/Vorklasse</li>
                        <li>Zeit für mich:</li>
                        <li>Lesen</li>
                        <li>Touch Up</li>
                        <li>Kurzer Spaziergang</li>
                        <li>Essen</li>
                        <li>Wenn dringlich: vorbereiten</li>
                    </ul>
                </div>
                <div class="day-part">
                    <h3>After School 🌖</h3>
                    <ul>
                        <li>Auf dem Weg nach Hause abschalten:</li>
                        <li>Mit Freundinnen reden</li>
                        <li>Musik oder Podcast</li>
                        <li>Lesen</li>
                        <li>Planen</li>
                        <li>Journal</li>
                        <li>Lernen (Nach-/Vorbereiten)</li>
                        <li>Runterkommen</li>
                        <li>Umziehen & Sachen aufräumen</li>
                        <li>Sport:</li>
                        <li>Gym</li>
                        <li>Kurse (Yoga etc.)</li>
                        <li>Home Workouts</li>
                        <li>Hula Hoop</li>
                        <li>Spaziergang</li>
                        <li>Duschen</li>
                        <li>Skin Care</li>
                        <li>Abschminken</li>
                        <li>Unreinheiten pflegen</li>
                        <li>Abendessen</li>
                        <li>1h lernen</li>
                        <li>Vorbereitungen für nächsten Tag:</li>
                        <li>Outfit rauslegen</li>
                        <li>Tasche packen</li>
                        <li>Essen zubereiten</li>
                        <li>Freizeit:</li>
                        <li>Telefonieren</li>
                        <li>Mit Mama reden</li>
                        <li>Vorhaben</li>
                        <li>Lesen</li>
                        <li>Raus gehen</li>
                        <li>Serie ansehen</li>
                        <li>Nightly Self Care:</li>
                        <li>Gua Sha</li>
                        <li>Säuren</li>
                        <li>Haare</li>
                        <li>21:30 Bettzeit</li>
                    </ul>
                </div>
            </div>
        </section>
        <section id="goals" class="section">
            <h2>Meine Ziele</h2>
            <div class="lists">
                <div class="list-item">
                    <h3>Langfristige Ziele</h3>
                    <ul>
                        <li>Beispielziel 1</li>
                        <li>Beispielziel 2</li>
                    </ul>
                </div>
                <div class="list-item">
                    <h3>Kurzfristige Ziele</h3>
                    <ul>
                        <li>Beispielziel 1</li>
                        <li>Beispielziel 2</li>
                    </ul>
                </div>
            </div>
        </section>
        <section id="ideas" class="section">
            <h2>Ideen</h2>
            <div class="ideas">
                <div class="idea-item">
                    <h3>Idee 1</h3>
                    <p>Beschreibung der Idee 1.</p>
                </div>
                <div class="idea-item">
                    <h3>Idee 2</h3>
                    <p>Beschreibung der Idee 2.</p>
                </div>
                <div class="idea-item">
                    <h3>Idee 3</h3>
                    <p>Beschreibung der Idee 3.</p>
                </div>
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Dein Name. Alle Rechte vorbehalten.</p>
    </footer>
</body>
</html>
