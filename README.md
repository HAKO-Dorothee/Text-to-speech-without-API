# Text-to-speech-without-API
Développement d’un outil de synthèse vocale en Python permettant de lire un texte avec différentes voix, langues et accents, avec réglage de la vitesse et du volume. Fonctionnement local sous Windows, sans API payante.

Le programme détecte automatiquement les voix disponibles dans Windows OneCore et affiche leurs langues et variantes régionales, comme le français de France, du Canada ou de Suisse. L’utilisateur choisit une voix par son numéro, saisit son texte, puis lance la lecture. La vitesse et le volume sont configurables dans le code.

Développé dans VS Code, le projet utilise win32com.client pour communiquer avec le moteur vocal Windows SAPI. Il intègre une validation du numéro de voix et du texte saisi afin de gérer les erreurs courantes.

Il permet d’explorer la synthèse vocale multilingue et de comparer l’effet des voix, des accents et des paramètres de lecture sur la compréhension et le confort d’écoute.
