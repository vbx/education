# Education - Exercices HTML

Projet simple pour stocker des exercices en HTML sans dependances. Chaque exercice peut etre ouvert directement dans un navigateur (sans serveur).

## Structure

- `index.html` : page d'accueil qui liste les matieres.
- `exercises/` : dossiers par matiere (Anglais, Physique, Francais, ...).
- `exercises/<Matiere>/` : pages HTML des exercices.

## Ajouter un exercice

1. Creer un nouveau fichier HTML dans le dossier de la matiere.
2. Ajouter un lien vers ce fichier dans `index.html` (ou creer une page d'index par matiere si besoin).
3. Garder les fichiers 100% statiques (pas de dependances, pas de build requis).

## Dev local (optionnel avec Vite)

Vite sert uniquement a avoir un rechargement auto pendant le dev.

```bash
npm install
npm run dev
```

Ensuite ouvrir l'URL indiquee par Vite.

## Ouvrir sans serveur

Vous pouvez ouvrir `index.html` ou n'importe quel exercice directement depuis le systeme de fichiers.
