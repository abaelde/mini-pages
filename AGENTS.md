# AGENTS.md

Petites pages statiques d'Aurélien, publiées avec GitHub Pages : https://abaelde.github.io/mini-pages/

## Structure

- `index.html` : sommaire. Une ligne par page, la plus récente en haut.
- Une page = un dossier avec son `index.html` (ex. `bapteme-victor/index.html` → https://abaelde.github.io/mini-pages/bapteme-victor/).
- `.nojekyll` : GitHub Pages sert les fichiers tels quels.

## Règles

- Le dépôt et le site sont **publics**. Pas d'adresse, de téléphone, de montant, d'heure ni de lieu d'un événement privé. Les prénoms et une date restent acceptés (choix d'Aurélien du 13 octobre 2026).
- Chaque page porte `<meta name="robots" content="noindex, nofollow">`.
- Chaque page est autonome (CSS et JS inline, polices Google Fonts seulement), en français, lisible sur téléphone, en clair comme en sombre.
- Ajouter toute nouvelle page au sommaire `index.html`.
- Publier = `git push` sur `main`. Le site se met à jour en une à deux minutes.
