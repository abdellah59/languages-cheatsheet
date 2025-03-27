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

## 📊 Tableaux
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
    </tr>
</table>
```


## 🔗 Liens utiles
- [MDN HTML](https://developer.mozilla.org/fr/docs/Web/HTML)
- [W3Schools HTML](https://www.w3schools.com/html/)

