# J'explore le monde 🌍

Trois jeux éducatifs gratuits de géographie, adaptés à chaque âge, de 3 à 14 ans.
`index.html` est la page d'accueil qui permet de choisir son activité.

## Les 3 activités

### 🐣 `geo_3_6.html` — Les amis des continents (3-6 ans)
Clique sur chaque continent coloré sur la carte pour découvrir :
- son nom,
- un animal qui y vit,
- un fait amusant,
- un bouton "🔊 Écouter" qui lit le texte à voix haute (API `speechSynthesis`
  du navigateur — aucun fichier audio requis, utile pour les enfants qui ne
  lisent pas encore).

Une étoile s'ajoute à chaque continent découvert. Une fois les 6 trouvés :
confettis 🎉 + bouton "Rejouer".

### 🧭 `geo_7_10.html` — Le jeu des capitales (7-10 ans)
Quiz à choix multiples associant pays et capitales (drapeaux inclus), avec
3 niveaux de difficulté (Facile / Moyen / Difficile), un score, une série de
bonnes réponses ("streak") et un chronomètre. Le meilleur score par niveau
est sauvegardé dans le navigateur (`localStorage`).

### 🌐 `geo_11_14.html` — Défi géo mondial (11-14 ans)
Défi mêlant 3 types de questions tirées au hasard : capitales, vrai ou faux
(mythes géographiques démystifiés, records, faits marquants) et monuments
célèbres à associer à leur pays. 3 longueurs de défi (8 / 12 / 16 questions),
badges (🥉🥈🥇💎) selon le score, explications après chaque réponse, et
meilleur score sauvegardé par longueur de défi.

## Structure du projet
```
index.html       -> page d'accueil (choix de l'âge)
geo_3_6.html      -> activité 3-6 ans
geo_7_10.html     -> activité 7-10 ans
geo_11_14.html    -> activité 11-14 ans
style.css        -> styles partagés (thème + composants de quiz)
```

## Idées pour continuer ce projet (dans VS Code)
- Ajouter d'autres langues (anglais, espagnol) comme dans "j_apprends_les_saveurs".
- Ajouter plus de pays/capitales dans les banques de questions (`geo_7_10.html`,
  `geo_11_14.html`) pour varier davantage les parties.
- Ajouter un mode "carte interactive" où l'élève place lui-même les pays.
- Ajouter un tableau des scores partagé (nécessiterait un petit backend).
- Déployer sur GitHub Pages (Settings > Pages > branche main > dossier racine).

## Licence
Voir LICENSE. Créé à but éducatif — merci de partager ces jeux gratuitement.
