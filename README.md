# Github-Users-API

>Un exercice pour vous familiariser avec les requêtes d'une ressource externe depuis un JavaScript client vers une API officielle en crossdomain.
>(Chercher des utilisateurs Github en fonction du langage de programmation et de leurs localisations.)

<img src="https://ipfs.infura.io/ipfs/QmUuVCrEiT34Yb89d44gz8fXPXAj8PT4zVze6m8LcF9hte" width="400" />

## Instructions

:bulb: Dans l'ordre il faudra:

- Utiliser `fetch()` (es6)
- Requêter les 100 premiers résultats (max) de la première page
- Requêter selon deux paramètres: langage et localisation
- Récupérer la liste d'utilisateurs au format `json`
- Afficher les informations basiques, le gravatar (en `img`) et le lien vers chacun des profils github
- Il n'y a pas besoin de créer de fonction. Placer son code dans le callback par défaut est suffisant
- Le CSS est déjà fourni
- Une fois que votre code est fonctionnel, il faut que l'utilisateur qui consulte votre page puisse changer les variables langage et localisation depuis la barre d'url (à la volée)

## Ressources externes

- Comment utiliser [fetch](https://developer.mozilla.org/fr/docs/Web/API/Fetch_API/Using_Fetch) (mdn)
- [https://developer.github.com/v3/search/#search-users](https://developer.github.com/v3/search/#search-users)
- La section `user` de la [documentation](https://help.github.com/en/github/searching-for-information-on-github/searching-users) de l'API Github
- Rappel sur [URLSearchParams](https://developer.mozilla.org/fr/docs/Web/API/URLSearchParams)