
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Booster - Service d'Abonnés</title>

    <!--
        Partie CSS : Styles pour l'apparence du site.
        Le code est placé directement ici pour éviter d'avoir un fichier séparé.
        Les couleurs ont été mises à jour pour respecter la palette blanc, rouge, noir et vert.
    -->
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #000000; /* Noir */
            color: #ffffff; /* Blanc */
            margin: 0;
            line-height: 1.6;
            display: flex;
            flex-direction: column;
            min-height: 100vh;
        }

        header {
            text-align: center;
            padding: 3rem 1rem;
            background-color: #111111;
            border-bottom: 3px solid #fe2c55; /* Rouge inspiré de TikTok */
        }

        header h1 {
            font-size: 3rem;
            color: #00ff66; /* Vert */
            margin-bottom: 0.5rem;
        }

        main {
            flex: 1;
            padding: 2rem;
            max-width: 1200px;
            margin: 0 auto;
            width: 100%;
        }

        .tarifs {
            text-align: center;
            margin-bottom: 3rem;
        }

        .tarifs-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
            margin-top: 2rem;
        }

        .carte-tarif {
            background-color: #111111;
            border: 1px solid #333333;
            border-radius: 10px;
            padding: 2rem;
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }

        .carte-tarif:hover {
            transform: translateY(-8px);
            box-shadow: 0 8px 20px rgba(254, 44, 85, 0.3); /* Ombre rouge */
        }

        .carte-tarif h3 {
            font-size: 1.5rem;
            color: #00ff66; /* Vert */
            margin-bottom: 0.5rem;
        }

        .prix {
            font-size: 2.2rem;
            font-weight: bold;
            color: #ffffff; /* Blanc */
            margin-top: 0;
        }

        .bouton-whatsapp, .bouton-footer {
            display: inline-block;
            background-color: #fe2c55; /* Rouge */
            color: #ffffff; /* Blanc */
            padding: 0.8rem 2rem;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            margin-top: 1rem;
            transition: background-color 0.3s ease, transform 0.3s ease;
            border: none;
        }

        .bouton-whatsapp:hover, .bouton-footer:hover {
            background-color: #d11e40; /* Rouge plus sombre au survol */
            transform: scale(1.05);
        }

        .video-container {
            text-align: center;
            margin-bottom: 3rem;
        }

        .video-container iframe {
            width: 100%;
            max-width: 800px;
            height: 450px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.5);
        }

        footer {
            text-align: center;
            padding: 2rem;
            background-color: #111111;
            border-top: 3px solid #fe2c55; /* Rouge */
        }

        footer a {
            color: #fe2c55; /* Rouge */
            text-decoration: none;
            font-weight: bold;
        }

        /* Adaptation pour les petits écrans (mobile) */
        @media (max-width: 768px) {
            header h1 {
                font-size: 2.5rem;
            }
            .video-container iframe {
                height: 250px;
            }
        }
    </style>
    <!-- On utilise une police moderne de Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

    <!-- Section de l'en-tête du site -->
    <header>
        <h1>Booster</h1>
        <p>Augmentez votre audience et votre visibilité sur les réseaux !</p>
    </header>

    <!-- Contenu principal du site -->
    <main>
        <!-- Section des tarifs -->
        <section class="tarifs">
            <h2>Nos Offres</h2>
            <div class="tarifs-grid">
                <!-- Carte pour l'offre 7 abonnés -->
                <div class="carte-tarif">
                    <h3>7 Abonnés</h3>
                    <p class="prix">50 FCFA</p>
                    <a href="https://wa.me/221785620453?text=Bonjour, je suis intéressé(e) par l'offre 7 abonnés à 50 FCFA." class="bouton-whatsapp">commander en envoyé un message sur watshapp 785620453</a>
                </div>
                <!-- Carte pour l'offre 15 abonnés -->
                <div class="carte-tarif">
                    <h3>15 Abonnés</h3>
                    <p class="prix">100 FCFA</p>
                    <a href="https://wa.me/221785620453?text=Bonjour, je suis intéressé(e) par l'offre 15 abonnés à 100 FCFA." class="bouton-whatsapp">commander en envoyé un message sur watshapp 785620453</a>
                </div>
                <!-- Carte pour l'offre 30 abonnés -->
                <div class="carte-tarif">
                    <h3>30 Abonnés</h3>
                    <p class="prix">200 FCFA</p>
                    <a href="https://wa.me/221785620453?text=Bonjour, je suis intéressé(e) par l'offre 30 abonnés à 200 FCFA." class="bouton-whatsapp">commander en envoyé un message sur watshapp 785620453</a>
                </div>
                <!-- Carte pour l'offre 60 abonnés -->
                <div class="carte-tarif">
                    <h3>60 Abonnés</h3>
                    <p class="prix">400 FCFA</p>
                    <a href="https://wa.me/221785620453?text=Bonjour, je suis intéressé(e) par l'offre 60 abonnés à 400 FCFA." class="bouton-whatsapp">commander en envoyé un message sur watshapp 785620453</a>
                </div>
            </div>
        </section>

        <!-- Section pour la vidéo -->
        <section class="video-container">
            <h2>Regardez la vidéo de présentation</h2>
            <!--
                Remplacez le "src" ci-dessous par l'URL de votre propre vidéo
                (Exemple d'URL YouTube : https://www.youtube.com/embed/votre_code_video)
            -->
            <iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </section>
    </main>

    <!-- Pied de page -->
    <footer>
        <p>Contactez-nous directement sur WhatsApp pour toute question.</p>
        <a href="https://wa.me/221785620453" class="bouton-footer">WhatsApp: 785620453</a>
    </footer>

    <!--
        Partie JavaScript : Ajoute de l'interactivité.
        Le code est placé à la fin du corps de page pour qu'il s'exécute après le chargement des éléments HTML.
    -->
    <script>
        // Ce code JavaScript simple sert d'exemple pour de futures fonctionnalités.
        // Pour l'instant, il ne fait qu'afficher un message dans la console du navigateur.
        console.log("Le site Booster est prêt !");

        // Exemple : un écouteur d'événement sur les boutons de commande
        const boutons = document.querySelectorAll('.bouton-whatsapp');

        boutons.forEach(bouton => {
            bouton.addEventListener('click', () => {
                // Cette ligne s'affichera dans la console du navigateur
                console.log("Un utilisateur a cliqué sur un bouton de commande.");
            });
        });
    </script>

</body>
</html>
