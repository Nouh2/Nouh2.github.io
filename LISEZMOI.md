# Site CV : Noe Chevalier-Tehraoui

Site en une seule page, bilingue (anglais par défaut, bouton FR), sans dépendance : un seul fichier `index.html`.

## Contenu du dossier

- `index.html` : le site complet.
- `cv-noe-chevalier-tehraoui-fr.pdf` : ton CV français, lié au bouton « Télécharger le CV » en version FR.
- **À ajouter** : `cv-noe-chevalier-tehraoui-en.pdf`, ton CV anglais (bouton « Download CV » en version EN). Garde exactement ce nom de fichier.

## Mettre le site en ligne (gratuit)

Option la plus simple, Netlify Drop : va sur app.netlify.com/drop et glisse-dépose ce dossier. Tu obtiens une adresse en quelques secondes.

Option GitHub Pages (recommandée, adresse du type nouh2.github.io) :
1. Crée un dépôt public sur GitHub et mets-y le contenu de ce dossier.
2. Settings > Pages > Source : branche `main`, dossier `/ (root)`.
3. Le site est en ligne quelques minutes après.

Tu peux ensuite brancher un nom de domaine (par ex. noe-chevalier.com) depuis les réglages de Netlify ou de GitHub Pages.

## Brief pour Claude Code

Ouvre ce dossier dans Claude Code et demande par exemple :

> Ce dossier contient mon site CV (index.html, un seul fichier, bilingue EN/FR via des attributs data-l="en" / data-l="fr"). Mets-le dans un dépôt Git, publie-le sur GitHub Pages et vérifie que les liens, le changement de langue et les PDF fonctionnent. Ne change pas le design.

Règles du site à respecter pour toute modification :
- Chaque texte existe en deux versions : un élément `data-l="en"` et un élément `data-l="fr"`. Toute nouvelle phrase doit avoir les deux.
- Style « carnet de labo » : encre bleue, croquis hachurés, annotations manuscrites (police Caveat). Pas de cartes arrondies identiques, pas de pastilles ni d'étiquettes en bulles.
- Aucun chiffre ni résultat qui ne figure pas dans le CV. Ne jamais publier les résultats de l'étude Inserm ni le nom de la revue visée.
- Couleurs dans les variables CSS en haut du fichier (mode clair et mode sombre).
