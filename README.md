# CECA DEV AI — versions officielles Windows

Ce dépôt public contient uniquement les installateurs compilés, signatures Tauri,
manifestes et notes de version. Le code source reste privé.

- [Dernière version stable](https://github.com/celenoca89110-eng/CECA-DEV-AI-Releases/releases/latest)
- [Télécharger la version stable Windows x64](https://github.com/celenoca89110-eng/CECA-DEV-AI-Releases/releases/latest/download/CECA-DEV-AI-Windows-x64-setup.exe)
- [Présentation et installation](https://cecabotweb-ceca2.vercel.app/projets/ceca-dev-ai)
- [Documentation](https://cecabotweb-ceca2.vercel.app/documentation/ceca-dev-ai)

## Canaux

Le canal Stable ne distribue pas de RC. Le canal Préversion est volontaire dans
les applications comportant ce réglage. Son manifeste `preview.json` n'est pas
le manifeste stable `latest.json` ; une RC publiée ne remplace pas la stable.
Les anciennes versions sans sélecteur exigent une première installation volontaire
d'une RC comportant les canaux, puis peuvent rechercher les RC suivantes dans
Paramètres → Mises à jour → Préversion. Aucune installation sans confirmation.

Les limites de validation de chaque artefact figurent dans ses notes de version.
Un téléchargement vérifié ne constitue pas une preuve d'installation réussie.
Conservez une sauvegarde avant d'installer une préversion.

La signature Tauri protège les mises à jour et lie l'artefact à sa version. Elle
ne remplace pas une signature Windows Authenticode : en son absence, SmartScreen
peut avertir. Ne désactivez ni l'antivirus, ni TLS, ni les contrôles Windows.
Aucun secret, clé privée, code privé ou paiement ne doit être ajouté à ce dépôt.
