# Blog de Yannis Haegeman

Site statique (HTML/CSS pur, sans framework ni build) inspiré du thème WordPress "Ury" :
photo + bio + liste d'articles dans une colonne latérale, article en pleine largeur à droite.

## Structure

```
index.html                                 page d'accueil (affiche le dernier article)
articles/comment-choisir-son-orientation.html
articles/reflexions-integration-prepa.html
assets/css/style.css                       feuille de style partagée
assets/img/                                 images (avatar + visuels d'articles, à remplacer par de vraies photos)
vercel.json                                 URLs propres (/articles/mon-article au lieu de .html)
```

## Déploiement sur Vercel

Aucune étape de build n'est nécessaire (site 100% statique). Deux options :

1. **Via GitHub (recommandé pour les mises à jour futures)** : pousser ce dossier dans un
   dépôt GitHub, puis l'importer une fois dans Vercel (vercel.com → Add New Project).
   Chaque nouveau `git push` republie automatiquement le site.
2. **Via la CLI Vercel** : depuis ce dossier, lancer `npx vercel` (puis `npx vercel --prod`
   pour la mise en ligne définitive).

## État actuel (15 septembre 2026)

Les deux articles sont des brouillons / notes de travail, volontairement courts, pour
avoir un aperçu fonctionnel du site avant de retravailler le contenu :

- *Comment choisir son orientation...* : notes de travail (le texte de l'accroche existant
  a été repris tel quel).
- *Réflexions sur l'enseignement de l'intégration en prépa* : article quasiment rédigé par
  ailleurs, en attente d'intégration complète.

Les icônes de contact (Instagram / Facebook / TikTok) et la photo de profil sont des
placeholders à remplacer par les vrais éléments.
