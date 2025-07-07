# Techium - Projet HTML de base

Bienvenue dans le projet **Techium**, une fausse entreprise qui va nous permettre d’apprendre à créer des pages web **uniquement avec HTML** (pas de CSS).

Ce projet contient plusieurs pages :
- `index.html` (Accueil)
- `about.html` (À propos)
- `services.html`
- `works.html`
- `contact.html`
- `article.html`
- `styleguide.html`

---

## 📄 Structure de base d’un fichier HTML

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Nom de la page</title>
  </head>
  <body>
    <!-- Contenu visible ici -->
  </body>
</html>
```

---

## 🔤 Titres et Paragraphes

```html
<h1>Titre principal</h1>
<h2>Sous-titre</h2>
<p>Ceci est un paragraphe.</p>
```

---

## 🔗 Liens et Images

```html
<a href="page.html">Aller à une autre page</a>
<img src="chemin/image.jpg" alt="Description de l’image">
```

---

## 📋 Listes

Liste non ordonnée :
```html
<ul>
  <li>Élément</li>
</ul>
```

Liste ordonnée :
```html
<ol>
  <li>Élément</li>
</ol>
```

---

## 🧱 Groupes de contenu

```html
<div>
  <p>Contenu ici</p>
</div>

<p>Du texte <span>avec un mot spécial</span>.</p>
```

---

## 🧭 Balises sémantiques

```html
<header>En-tête</header>
<nav>Menu</nav>
<main>Contenu principal</main>
<section>Section de contenu</section>
<article>Article de blog</article>
<aside>Encadré ou info secondaire</aside>
<footer>Pied de page</footer>
```

---

## 🎵 Médias

Vidéo :
```html
<video controls>
  <source src="video.mp4" type="video/mp4">
</video>
```

Audio :
```html
<audio controls>
  <source src="audio.mp3" type="audio/mpeg">
</audio>
```

---

## 🌐 Contenu externe (iframe)

```html
<iframe src="https://example.com"></iframe>
```

---

## ➖ Ligne horizontale

```html
<hr>
```

---

## 🗂️ Tableaux

```html
<table>
  <thead>
    <tr><th>Nom</th><th>Âge</th></tr>
  </thead>
  <tbody>
    <tr><td>Lucie</td><td>22</td></tr>
  </tbody>
</table>
```

---

## 🖋️ Texte en gras / italique

```html
<b>Gras</b> ou <strong>Important</strong>
<i>Italique</i> ou <em>Accentué</em>
```

---

## ✅ Résumé des balises

| Balise       | Description |
|--------------|-------------|
| `<h1>` à `<h6>` | Titres |
| `<p>`        | Paragraphe |
| `<a>`        | Lien |
| `<img>`      | Image |
| `<ul>` / `<ol>` / `<li>` | Listes |
| `<div>`      | Conteneur |
| `<span>`     | Mot dans une phrase |
| `<header>`   | En-tête |
| `<footer>`   | Pied de page |
| `<main>`     | Contenu principal |
| `<section>`  | Section |
| `<article>`  | Article |
| `<nav>`      | Menu |
| `<aside>`    | Info secondaire |
| `<video>` / `<audio>` | Médias |
| `<iframe>`   | Contenu externe |
| `<hr>`       | Ligne horizontale |
| `<table>`    | Tableau |


Pour tester :
ttps://validator.w3.org


TASK 0 :

Create your first HTML file 0-index.html with:

- Add the doctype on the first line (without any comment)
- After the doctype, open and close a html tag
- Add the language tag, specify English for ISO language code and add the direction tag (ltr = left to right, or rtl = right to left) on the html tag.
- Open your file in your browser (the page should be blank)

TASK 1 :

Structure your webpage

- Copy the content of 0-index.html into 1-index.html
-Create the head and body sections
-inside the html tag, create the head and body tags (empty) in this order

TASK 2 :

Copy the content of 1-index.html into 2-index.html



Meta charset:

add a meta tag inside the head:
add the charset attribute with the value utf-8
Viewport:

add a meta tag inside the head:
add an attribute name on the tag and specify that it is the meta viewport
add the key width with the value device-width
add the key initial-scale with the value 1.0
add the key viewport-fit with the value cover
Title:

add the title tag just after the meta viewport with value: Homepage - Techium
Description:

add a meta tag inside the head section
add an attribute name on the tag and specify that is the meta description
add another attribute called content
add the following description: Techium is a digital agency
Favicons:

download the image above to use as a favicon
Use the tool at https://realfavicongenerator.net/ to generate all the favicon formats
take the favicon.ico and favicon.png and place these at the root of your project directory, so that it is siblings with your [0-9]+-index.html files.
inside the head, create 2 link tags with these 3 attributes: rel, type, and href.
the first link tag:
rel: icon
type: image/x-icon
href: ./favicon.ico
the second link tag:
rel: icon
type: image/png
href: ./favicon.png