<!DOCTYPE html>
<html lang="cs">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>American Experience - Cestovní Agentura</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="header-background">
            <h1 class="company-name">American Experience</h1>
            <div class="fireworks"></div>
        </div>
    </header>

    <section class="owner-info">
        <h2>O majiteli</h2>
        <p>
            Panagiotiss Matthaios Karandreas, narozen 29. srpna 2006 v Athínách, Řecko, je majitelem cestovní agentury "American Experience".
            Studuje na SSGH v Praze, Česká republika, a toto je jeho projekt.
        </p>
    </section>

    <section class="usa-info">
        <h2>O Spojených státech amerických</h2>
        <p>
            Spojené státy americké (USA) jsou federální republikou, která se nachází v severní Americe. S 50 státy a hlavním městem Washington, D.C.,
            jsou USA jednou z nejvlivnějších zemí na světě. Znáte známé památky jako Socha Svobody, Bílý dům a Grand Canyon.
        </p>
    </section>

    <footer>
        <p>Kontaktujte nás: info@americanexperience.com</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    position: relative;
    background-image: url('usa-flag.jpg'); /* Replace with the USA flag image */
    background-size: cover;
    background-position: center;
    height: 300px;
    color: white;
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.company-name {
    font-size: 3rem;
    font-weight: bold;
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
}

.fireworks {
    position: absolute;
    top: 0;
    right: 0;
    width: 100%;
    height: 100%;
    background-image: url('fireworks.png'); /* Replace with fireworks animation or image */
    background-size: cover;
    animation: fireworks 1s ease-in-out infinite;
}

@keyframes fireworks {
    0% { opacity: 0; }
    50% { opacity: 1; }
    100% { opacity: 0; }
}

section {
    padding: 20px;
    margin: 20px;
    background-color: white;
    border-radius: 8px;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

h2 {
    font-size: 2rem;
    margin-bottom: 15px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
}
