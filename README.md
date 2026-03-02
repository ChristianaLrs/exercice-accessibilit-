# Exercice d'accessibilité des contenus

## Équipe 
- Christiana Larisse
- Nouhourou Sita Ouattara

## Objectifs
- Expérimenter le versionnage de fichiers avec GIT
- Acquérir des compétences en accessibilité des contenus

## Prérequis
- Avoir lu et pris connaissance des notes du cours 
- Avoir installé l'outil CCA (colour-contrast-analyzer)
- Avoir un compte GitHub
- Avoir installé et configurer GIT sur votre ordinateur

## Instructions

### 0. 
- Initialiser un dépôt GIT dans le dossier du projet
- Créer un fichier `index.html` et un fichier `style.css`

### 1.	Donner une alternative textuelle aux images

#### 1.1 Baliser dans le fichier `index.html` les images du dossier `1-textes-alternatifs` 

Pour vous guider dans le choix des balises, des attributs et des valeurs d'attributs, utiliser l'arbre de décision et référez-vous aux notes de cours.

#### 1.2 Évaluer la pertinence des contenus textuels alternatifs

Pour chacune des pages ci-dessous:
* __Utiliser la barre d'outil de développement pour inspecter les images__ et juger de la qualité des attributs *alt*. __Prendre une capture-écran et la joindre ci-dessous.__
*  __Les textes alternatifs sont-ils adéquats ?__ Commenter votre observation. Pourrait-on faire mieux ? Donnez un exemple de ce que vous proposeriez.
 
[capture-écran-à-ajouter]()
- https://www.lesoleil.com/  
----- Ils ne faut pas mettre le meme texte aux alt 
----- voir fichier pour les captures d ecran
----- Oui on peut faire mieux en ajoutant des ficaption et en ajoutant des alt.
----- Mettre du texte dans les liens pour que les utilisateurs puissent naviguer dns de bonnes conditions
[capture-écran-à-ajouter]()
- https://www.rad.ca/  
-----  faire attention aux différents contrastes de couleurs.
----- les zones de references ne sont pas bonnes
----- deux images cote à cote ont le meme texte alternatif
 
 

### 2. Structurer avec les h1-h6 une table des matières

#### 2.1 Vérifier la structure

D’après les captures-écrans que vous trouverez dans le dossier __images/2-table-des-matieres_h1-h6/2-1/__, est-ce que la table des matières du document est correcte?  

Sinon, expliquez le problème en vous basant sur les règles de base énoncées dans les notes de cours. 

__Tutoriel sur les formulaires du w3c__  
[Article](images/2-table-des-matieres_h1-h6/2-1/tuto-form-w3c.pdf)  
[Table des matières (outline)](images/2-table-des-matieres_h1-h6/2-1/tuto-form-w3c-outline.png) 

Réponse : 

---- Oui elle est correct parce que l'on peut bien  voir ce qu'il y'a d'écrit dessus en plus d'eytrre mise. en evidence en gros.De plus, une fois l'option cliqué elle change de couleur pour indiqué à la personne que c'est cette option qu'elle a choisi.
----
----

__L’affaire Savtchenko__ 
[Article](images/2-table-des-matieres_h1-h6/2-1/article-savtchenko.pdf)  
[Table des matières (outline)](images/2-table-des-matieres_h1-h6/2-1/article-savtchenko-outline.png) 
  
Réponse : 

---- Non elle est pas correvct parce que l'écriture est presque illisible en plus d'avoir beaucoup de contenu qui qui serven à rien on retrouve beaucoup trop^d'information impossible de se retrouver.
----
----


#### 2.2 S'exercer à bien structurer

- Ouvrir la capture-écran [concevoir-un-design-sans-la-couleur](images/2-table-des-matieres_h1-h6/2-2/concevoir-un-design-sans-la-couleur.pdf) dans le logiciel PhotoShop.  
- Ajouter un calque de blanc à 50% de transparence
- Dans un 3e calque, par-dessus, identifiez les titres et leurs niveaux (h1-h6) de manière voyante (couleur rouge et font-size suffisant)
- Sauvegarder au format .png dans le même dossier.
- [Relier ce fichier-réponse ici]()

### 3. Baliser un tableau de données pour qu’il soit accessible

D’après la capture-écran et le texte fourni dans le dossier [3-tableau-de-donnees](images/3-tableau-de-donnees), balisez de manière accessible ce tableau de données.  
  
Votre tableau de données doit comporter un titre (caption) : 

> "Recommandations de consommation de poissons selon l’âge, le sexe et la condition physique".  


Les __entêtes de rangées et de colonnes__ doivent être balisées comme des `<th>` plutôt que des `<td>` et puisque le tableau est *complexe*, vous devez utiliser des attributs `id` dans les `<th>`. 

Chaque cellule `<td>` du tableau doit avoir un attribut headers avec comme valeur(s), le ou les identifiants de ses entêtes de colonnes et de rangées.

Styler le tableau conformément au fichier [consommation-poissons.pdf](images/3-tableau-de-donnees/consommation-poissons.pdf).

#### Ressources
•	balisage accessible d’un tableau (voir les notes du cours)
•	balisage html : https://www.w3schools.com/TAGs/tag_table.asp
•	balisage css de tableau: https://www.w3schools.com/css/css_table.asp





