# GameClips

Enregistreur de clips de jeu pour Windows 10/11. Il garde en continu les dernières minutes de
jeu et permet d'en faire un clip à tout moment : par raccourci, depuis l'overlay en jeu, ou
après coup depuis la timeline de la session.

*A game clip recorder for Windows 10/11: it keeps the last minutes of play and lets you clip
them at any time, with a hotkey, from the in-game overlay, or later from the session's
timeline. The app is available in English and French.*

## Télécharger / Download

Dernière version : **[Releases](https://github.com/TheJordanDev/GameClips-releases/releases/latest)**

| Fichier | Pour qui |
|---|---|
| `GameClips_<version>_x64-setup.exe` | **Installeur** : à installer, se lance avec Windows si tu veux. |
| `GameClips-<version>-portable.zip` | **Portable** : à dézipper n'importe où ; les réglages restent à côté de l'exe. |
| `SHA256SUMS.txt` | Les empreintes, pour vérifier les téléchargements. |

- **Les fichiers se terminant par `-unsigned` ne sont pas signés numériquement.** Au premier
  lancement, Windows SmartScreen affiche « Windows a protégé votre ordinateur ». Il suffit de
  cliquer sur **Informations complémentaires**, puis **Exécuter quand même**.
- **FFmpeg** n'est pas inclus : l'app propose de le télécharger au premier lancement (build
  LGPL).
- **Il faut** Windows 10 version 2004 ou plus récent, et WebView2, déjà présent sur Windows 10
  et 11.

## Fonctions

- **Profils** : un profil global, puis un par jeu qui en surcharge les réglages. Les apps liées
  (client, launcher) sont enregistrées avec les réglages de leur jeu, et le jeu passe toujours
  avant.
- **Audio** : jeu, apps choisies (Discord, navigateur…), système et micro, sur des pistes
  séparées ou mixées.
- **Bibliothèque** : lecture, découpe sans réencodage, export compressé (taille cible, par
  exemple 10 Mo pour Discord), choix et mixage des pistes.
- **Overlay en jeu** : timeline du buffer, marqueurs, clip manuel.

## Licence / License

[PolyForm Strict 1.0.0](LICENSE) © TheJordanDev.

- **Permis** : télécharger et utiliser l'app, pour un usage non commercial.
- **Interdit** : la redistribuer ou en publier une version modifiée.

*Free to download and use for noncommercial purposes; redistribution and modified versions are
not allowed.*
