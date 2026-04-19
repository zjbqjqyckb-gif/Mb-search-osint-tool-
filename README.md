# Mb-search-osint-tool-
MB-SEARCH est une console OSINT immersive au style Cyberpunk. Elle automatise la collecte de renseignements via Shodan, IntelX, et MatchID. Centralisez vos scans d'e-mails, IP et identités pour détecter fuites de données, décès ou infrastructures exposées. Une interface radicale pour une analyse de cible rapide et efficace.
💀 MB-SEARCH - Guide d'Utilisation Officiel
MB-SEARCH est une console d'intelligence OSINT (Open Source Intelligence) prête à l'emploi. Vos clés API Shodan et IntelX sont déjà configurées dans le noyau du système.
🛠️ Configuration & Accès
Le fichier est autonome (self-contained). Pour l'utiliser :
1.	Enregistrez le fichier .html sur votre appareil.
2.	Ouvrez-le avec n'importe quel navigateur moderne (Safari, Chrome, Firefox).
🔒 Utilisation avec Orbot (Recommandé pour iPad/Mobile)
Pour accéder aux données du Dark Web et contourner certaines restrictions réseau, l'utilisation d'Orbot est nécessaire :
1.	Installation : Téléchargez Orbot sur l'App Store (iOS) ou Play Store.
2.	Activation : Lancez Orbot et activez le mode "VPN" (ou le démarrage de Tor).
3.	Configuration : Assurez-vous que votre navigateur (Safari ou Chrome) passe par le tunnel Orbot.
4.	Avantage : Cela permet de router vos requêtes via le réseau Tor, facilitant l'accès aux recherches liées à la section Dark Web Forums.
📱 Spécificités iPad
L'iPad possède des couches de sécurité strictes :
• Module MatchID (INSEE) : Fonctionne nativement pour vérifier l'état civil.
• Modules Shodan & IntelX : Si les résultats n'apparaissent pas malgré vos clés, cela est dû au blocage CORS.
• Solution : Utilisez une application de gestion de fichiers avec navigateur intégré (type Koder ou Documents by Readdle) en combinaison avec Orbot.
💻 Utilisation sur Ordinateur
Pour débrider totalement la puissance de MB-SEARCH :
1.	Installez l'extension "Allow CORS: Access-Control-Allow-Origin".
2.	Activez l'extension (l'icône doit passer au vert).
3.	Lancez votre recherche pour permettre l'interrogation directe des APIs Shodan et IntelX.
🚀 Procédure de Recherche
1.	Cible : Saisissez un nom, un e-mail, une IP ou un domaine dans le champ Acquisition de Cible.
2.	Lancement : Cliquez sur "INITIER CHASSE".
3.	Analyse :
• Le Terminal affiche le journal des connexions en temps réel.
• Le Rapport d'Intelligence compile les statistiques (Fuites, Devices, Décès).
• Les Données Brutes (en bas) permettent d'analyser les flux JSON extraits.
⚠️ Rappels de Sécurité
• Clés API : Vos clés sont inscrites dans le code. Ne partagez pas ce fichier.
• Éthique : L'utilisateur est seul responsable de l'exploitation des données collectées.
Statut du Système : OPÉRATIONNEL
Sources Actives : MatchID, Shodan, IntelX, DarkWeb
