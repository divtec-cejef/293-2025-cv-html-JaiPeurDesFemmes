## A) Supprimer le contenu discriminatoire / insultant
- Une phrase contient une attaque visant l’orientation sexuelle
- Veuillez la supprimer immédiatement et reformuler de manière respectueuse (sans insultes, sans discrimination)

## B) Favicons : utiliser `./` (fichiers à la racine)
- Il manque les favicons dans les fichiers
- Vos favicons utilisent `/...` (chemins absolus)
- Veuillez utiliser `./...` si les fichiers sont à la racine
- Exemple :
```
<link rel="icon" type="image/png" sizes="32x32" href="./favicon-32x32.png">
```
- Même principe pour les autres (`apple-touch-icon`, `manifest`, etc.)

## C) Photo dans le header : ouverture dans un nouvel onglet + sécurité
- Veuillez faire en sorte qu’un clic ouvre l’image dans un nouvel onglet
- Ajoutez `target="_blank"` et `rel="noopener noreferrer"`
- Exemple :
```
<a class="logo" href="./img/shocked-miles-morales-thumbnail-url-7p483p.jpg" target="_blank" rel="noopener noreferrer">
  <img class="profil" src="./img/shocked-miles-morales-thumbnail-url-7p483p.jpg" alt="Photo de Leonardo Varela">
</a>
```

## E) Footer : ajouter l’e-mail en `mailto:`
- Le footer doit contenir `&copy;2025` + votre e-mail cliquable
- Exemple :
```
<footer>
  &copy;2025 Leonardo Varela —
  <a href="mailto:prenom.nom@email.com">prenom.nom@email.com</a>
</footer>
```

## Autres
- Attention à l'indentation et à la lisibilité du code
- description dans la balise `<meta>` dans le '<head>'
