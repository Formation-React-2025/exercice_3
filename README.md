# Formation React 2025

## Exercice 3 - Création d'un composant avec state

### 1 - Initialisation du projet
Plusieurs possibilités :
- Continuer sur le même projet
- Télécharger le projet initialisé depuis le GitHub [Formation React 2025](https://github.com/orgs/Formation-React-2025/repositories) :
    - ```git clone https://github.com/Formation-React-2025/exercice_3.git```

### 2 - Mise à jour de variable
- Dans le package ```./src/features/exercice-3/components/on-click-button-with-state```, créer un composant `OnClickButtonWithState` :
- Le composant est iso au composant `OnClickButton` à la différence qu'il utilise le hook `useState` pour la gestion de sa variable.
- Appeler le composant dans `App.jsx`
- Que constatez-vous ?

### 3 - Création d'un composant avec state
- Dans le package ```./src/features/exercice-3/pages```, créer le composant ```Exercice3Page```.
- Titre : "Exercice 3 - Création d'un composant avec state"
- Le composant retournera un formulaire avec deux champs de saisie de type ```text``` et un bouton de type ```submit```.
-  Les champs seront ```controlled``` (i.e. leurs valeurs seront gérées au travers d’un « state » React) et ```required```
-  Les libellés des champs seront les suivants :
    - « Nom »
    - « Prénom »
- Le bouton portera la mention « Enregistrer ».

- À la soumission du formulaire, contrôler que les champs obligatoires sont bien renseignés. Si ce n’est pas le cas, afficher les champs en rouge avec le message « Le champ est obligatoire ».

- Dans le fichier ```./src/App.jsx```, appeler le composant.

<u>Notes :</u>
- Afin de ne pas propager l’évènement de validation du formulaire, on pourra utiliser la méthode ```e.preventDefault()```.
- Nous pourrons utiliser du CSS pour gérer les couleurs ou bien utiliser la props `style`
