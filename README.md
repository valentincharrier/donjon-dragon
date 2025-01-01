# Donjon Dragon

## Prompt permettant de créer l'application
```
* Je vais te donner une liste de 5 catégories qui contiennent chacun plusieurs items. La probabilité de tomber aléatoirement sur une catégorie est déterminé par la clé probabilite de la catégorie.
* Chaque item de catégorie à une clé probabilite permettant de déterminer dans l'item qui sera la probabilité de tomber sur cette item.
* Tu auras une clé qui permet de savoir si un item peut appartenir uniquement aux armes contondantes. sinon l'item peut appartenir aux armes tranchantes/perforantes et aux armes contondantes.

Exemple d'une catégorie type:

[
 { "name": "Catégorie n°1",
   "probabilite": 0.2,
   "items": [
    {
      "name": "Nom item 1",
      "descripion": "description de l'item n°1",
      "isArmeContondantes": true,
      "probabilite": 0.2
    },
     {
      "name": "Nom item 2",
      "descripion": "description de l'item n°2",
      "isArmeContondantes": false,
      "probabilite": 0.5
    }
   ]
 },
 { "name": "Catégorie n°1=2",
   "probabilite": 0.2,
   "items": [
    {
      "name": "Nom item 1",
      "descripion": "description de l'item n°1",
      "isArmeContondantes": false,
      "probabilite": 0.1
    },
     {
      "name": "Nom item 2",
      "descripion": "description de l'item n°2",
      "isArmeContondantes": false,
      "probabilite": 0.6
    }
   ]
 },
]

Tu vas créer un fichier html, css, javascript permettant d'ajouter deux boutons. Le premier aura d'écrit "Armes Tranchantes/Perforantes" et lors du click, tu choisiras aléatoirement une catégorie et un item en fonction des probabilité déterminé dans les données. Le 2eme bouton aura d'écrit "Armes Contondantes" et lors du click du choisiras aléatoirement une catégorie et un item en fonction des probabilité déterminé dans les données en ne selectionnant pas les items interdit (mentionné par la clé isArmeContondantes
```