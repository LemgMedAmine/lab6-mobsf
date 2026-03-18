# lab6-mobsf
<img width="1913" height="769" alt="Capture d&#39;écran 2026-03-18 011059" src="https://github.com/user-attachments/assets/7a7a2c78-8fc0-4c5e-a8bb-4a1ab5ebf23d" />

Ce screen montre un résumé de l’application analysée avec MobSF :
Nom de l’APK et taille

Hash (MD5, SHA1, SHA256)

Nom de l’application et package

Score de sécurité : 40/100 → faible

Indique que l’application contient plusieurs failles.

<img width="1902" height="591" alt="Capture d&#39;écran 2026-03-18 011129" src="https://github.com/user-attachments/assets/bb438224-efb6-4480-8597-f433770b59dc" />

Ce screen montre l’analyse du certificat :

Application signée avec un certificat debug (HIGH)

Signature valide mais non sécurisée

Une app ne doit jamais être publiée avec un certificat debug.

<img width="1823" height="535" alt="Capture d&#39;écran 2026-03-18 011144" src="https://github.com/user-attachments/assets/fd572f4e-9150-4e40-9ab7-675caff6464d" />

Ce screen liste plusieurs failles :
Debug activé (HIGH)

→ Permet de connecter un debugger et analyser l’app facilement

Backup autorisé (WARNING)

→ Les données peuvent être extraites via ADB

Mode test actif (HIGH)

→ Peut exposer des fonctionnalités internes

<img width="1795" height="537" alt="Capture d&#39;écran 2026-03-18 011204" src="https://github.com/user-attachments/assets/ea85e558-7976-4f1b-ba7b-c3bfd3dbc8cd" />

Ce screen montre d’autres problèmes :

Activities non protégées (WARNING)

→ Accessibles par d’autres applications

Broadcast Receiver exposé (WARNING)

→ Peut être utilisé par des apps malveillantes

Mauvaise gestion des permissions et exposition des composants.
