# SendToFreebox

Cette extension permet les fonctions suivantes:

  - Clic droit sur une URL pour envoyer vers l'appli _Téléchargement_ du Freebox Serveur
  - Lister les téléchargements en cours
  - Gestion simple des téléchargements

## Droits sur FreeboxOS

À noter que cette extension va ajouter une application sur votre Freebox (http://mafreebox.freebox.fr > "Paramètres de la Freebox" > "Mode Avancé" > "Gestion des Accès" > "Applications") nommée "SendToFreebox 4 Extension".

À savoir :

  - Les droits de cette application sont les droits par défaut donnés par Free, et il n'est pas possible de les modifier de façon programmatique… Cela signifie qu'on ne peut pas demander moins de droits !
  - L'application a des droits tels que "Accès au journal d'appels" et "Accès à la base de contacts de la Freebox" : en aucun cas ces informations sont utilisées par l'extension ! Vous pouvez tout à fait décocher ces cases.

En théorie les seuls droits nécessaires sont : "Accès au gestionnaire de téléchargements" et "Accès aux fichiers de la Freebox". Vous pouvez donc décocher les autres cases.

Concernant les droits donnés par défaut à l'application, je vous invite à aller vous plaindre sur le bugtracker de Free : https://dev.freebox.fr/bugs/task/30558

## Questions

Si vous avez des questions, des problèmes ou des demandes d'amélioration, merci de soumettre une _issue_ sur la [page dédiée](https://github.com/garoloup/SendToFreebox/issues).

## Développement

Afin de tester ce code dans votre navigateur sans passer par le store, vous devez télécharger le répertoire en cliquant sur le bouton "Clone or download", puis "Download Zip".

Dézipper le répertoire téléchargé, puis, selon votre navigateur :
  - Pour Firefox :
    - Ouvrir [about:debugging](about:debugging)
    - Cliquer sur **"Ce Firefox"**
    - Cliquer sur **"Charger un module complémentaire temporaire…"**
    - Sélectionner le fichier `manifest.json`
  - Pour Chrome :
    - Ouvrir [chrome://extensions/](chrome://extensions/)
    - Cliquer sur **"Mode Développeur"** (en haut à droite)
    - Cliquer sur **"Charger l'extension non empaquetée"**
    - Sélectionner le répertoire téléchargé précédemment
