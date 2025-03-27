# 📝 Cheat Sheet HTML

## 📌 Introduction
HTML (HyperText Markup Language) est le langage utilisé pour structurer le contenu des pages web.

## 🛠 Structure de base

```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon site</title>
</head>
<body>
    <h1>Bienvenue sur mon site</h1>
    <p>Ceci est un paragraphe.</p>
</body>
</html>
```
## 🔖 Principales balises HTML

### 📂 Structure
- `<!DOCTYPE html>` : Déclare la version HTML5
- `<html>` : Élément racine
- `<head>` : Métadonnées
- `<body>` : Contenu visible

### 🏷 Titres et Textes
- `<h1>` à `<h6>` : Titres (h1 = plus important)
- `<p>` : Paragraphe
- `<strong>` : Texte en gras
- `<em>` : Texte en italique
- `<br>` : Saut de ligne
- `<hr>` : Ligne horizontale

## 🔗 Liens et Médias
- `<a href="URL">` : Lien hypertexte
- `<img src="image.jpg" alt="Description">` : Image
- `<video src="video.mp4" controls>` : Vidéo
- `<audio src="audio.mp3" controls>` : Audio

### 📦 Listes
- Liste ordonnée :
  ```html
  <ol>
      <li>Élément 1</li>
      <li>Élément 2</li>
  </ol>
  ```
- Liste non ordonnée :
  ```html
  <ul>
      <li>Élément A</li>
      <li>Élément B</li>
  </ul>
  ```

## 🏗️ Parents et Enfants
Les balises HTML suivent une structure parent/enfant. Exemple :
```html
<div>
    <p>Texte dans un div</p>
</div>
```

### 📊 Tableaux
Les tableaux permettent d'organiser des données sous forme de grille.

```html
<table border="1">
    <tr>
        <th>Nom</th>
        <th>Âge</th>
        <th>Ville</th>
    </tr>
    <tr>
        <td>Jean</td>
        <td>25</td>
        <td>Paris</td>
    </tr>M
</table>
```
    📌 Balises importantes :

    - <table> : Définit un tableau
    - <thead> : Regroupe l'en-tête du tableau
    - <tbody> : Contient les lignes du tableau
    - <tr> : Définit une ligne 
    - <th> : Définit une cellule d’en-tête (gras et centré par défaut) 
    - <td> : Définit une cellule standard

🔹 Fusionner des cellules
```html
<td colspan="2">Fusion de 2 colonnes</td> <!-- Fusion horizontale -->
<td rowspan="2">Fusion de 2 lignes</td> <!-- Fusion verticale -->
```

## 🔤 Inputs

Les inputs permettent de récupérer des données utilisateur via un formulaire.

```html
<input type="text" placeholder="Votre nom">
<input type="email" placeholder="Votre email">
<input type="password" placeholder="Mot de passe">
<input type="number" min="1" max="100">
<input type="date">
<input type="file">
<input type="color">
```
    📌 Attributs importants :

    - placeholder : Texte indicatif dans l'input
    - required : Rend l’input obligatoire
    - min, max : Définit les valeurs minimales et maximales
    - step : Incrémente une valeur (ex. step="2" pour des valeurs paires)

## 3. Les Formulaires et la Validation

Un formulaire est défini par```<form>```. Il permet d’envoyer des données via GET ou POST.

```html
<form action="traitement.php" method="POST">
    <label for="nom">Nom :</label>
    <input type="text" id="nom" name="nom" required>

    <label for="email">Email :</label>
    <input type="email" id="email" name="email" required>

    <input type="submit" value="Envoyer">
</form>

```

    📌 Attributs importants :

    - action : URL où envoyer les données
    - method="GET" : Affiche les données dans l’URL
    - method="POST" : Envoie les données en arrière-plan
    - required : Rend un champ obligatoire

## Dropdowns, Boutons Radio et Checkbox

🎚 Liste déroulante (Dropdown)

```html
<select name="pays">
    <option value="france">France</option>
    <option value="canada">Canada</option>
    <option value="japon">Japon</option>
</select>
```

- Boutons radio (choix unique)
```html
<input type="radio" id="homme" name="genre" value="homme">
<label for="homme">Homme</label>

<input type="radio" id="femme" name="genre" value="femme">
<label for="femme">Femme</label>
```
    📌 Tous les boutons radio d’un même groupe doivent avoir le même name pour un choix unique.


- Checkbox (choix multiples)
```html
<input type="checkbox" id="voiture" name="transport" value="voiture">
<label for="voiture">Voiture</label>

<input type="checkbox" id="velo" name="transport" value="velo">
<label for="velo">Vélo</label>
```
    📌 Chaque checkbox fonctionne indépendamment contrairement aux boutons radio.


## 6. Insérer une Vidéo en HTML

- Vidéo YouTube
```html 
<iframe width="560" height="315" src="https://www.youtube.com/embed/ID_DE_LA_VIDEO" allowfullscreen></iframe>
```
- Vdéo locale
```html
<video controls>
    <source src="video.mp4" type="video/mp4">
    Votre navigateur ne supporte pas la vidéo.
</video>
```
    📌 Attributs utiles :

    - controls : Affiche les boutons de lecture
    - autoplay : Démarre la lecture automsatique
    - loop : Lit en boucle
    - muted : Désactive le son

    
## 🔗 Liens utiles
- [MDN HTML](https://developer.mozilla.org/fr/docs/Web/HTML)
- [W3Schools HTML](https://www.w3schools.com/html/)

