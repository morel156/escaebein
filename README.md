# ESCAE-BÉNIN

Site vitrine statique (HTML/CSS) pour l'ESCAE-BÉNIN, présenté dans le contenu comme « premier des universités privées du Bénin, École Supérieure de Commerce et d'Administration des Entreprises », avec des annexes à Calavi, Porto-Novo et Savè.

## Contenu du site

Le site comporte cinq pages statiques, reliées par un menu commun (header) et partageant le même pied de page (footer) :

- **index.html** — Accueil : présentation générale de l'école et formulaire de commentaire.
- **index1.html** — Qui sommes-nous : présentation de l'école et de ses annexes.
- **index2.html** — Nos filières : aperçu des filières proposées, avec les tarifs (400 000 F pour les étudiants locaux, 600 000 F pour les étudiants étrangers).
- **index3.html** — Ma filière : zoom sur la filière SIL (Systèmes Informatiques et Logiciels) et ses débouchés (systèmes d'information, sécurité informatique, intelligence artificielle, génie logiciel, cybersécurité).
- **index4.html** — Nous contacter : coordonnées (e-mail et téléphones).

Chaque page suit la même structure : `<header>` (logo + menu de navigation à 5 liens), `<section>` (contenu propre à la page, avec images), `<footer>` (mention de copyright).

## Stack technique

- HTML5
- CSS3 (feuille de style unique `style.css`)
- Aucun framework, aucune dépendance, aucun backend (le formulaire de la page d'accueil pointe vers un `traitement.php` non présent dans le dépôt)

## Voir le site en local

Aucune installation n'est nécessaire. Deux options :

1. **Ouvrir directement le fichier** : double-cliquer sur `index.html` (ou l'ouvrir depuis le navigateur avec `Ctrl+O`).
2. **Servir le dossier** (recommandé pour un rendu fidèle) :
   ```bash
   python -m http.server 8000
   ```
   puis ouvrir `http://localhost:8000` dans le navigateur.

## Fichiers

| Fichier | Rôle |
|---|---|
| `index.html` à `index4.html` | Les cinq pages du site |
| `style.css` | Styles partagés par toutes les pages |
| `photo1.jpg`, `contact.jpg`, `filière1.jpg`, `filière2.jpg`, `mafilière.jpg` | Images utilisées dans les pages |
