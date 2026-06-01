# Mon Petit Jardin 🌸

Une petite application web (standalone, hors-ligne) regroupant 9 jeux et outils tendres,
chacun pensé autour d'un profil neurodéveloppemental précis : on s'appuie sur les forces
(attention visuelle) et on évite les fragilités (mémoire de travail, lecture, calcul, chrono, son).

## Les outils

**Pour se réveiller** — 🌳 Le jardin (cherche & trouve)
**Pour se détendre** — 🎈 Respire avec moi (cohérence cardiaque) · 🫧 Les bulles tranquilles · 🌀 Le kaléidoscope
**Pour s'amuser à regarder** — 👀 Trouve les jumeaux (discrimination visuelle, sans mémoire de travail)
**Pour le cœur** — 🎡 La roue des émotions (affect labeling) · ⭐ Mes fiertés
**Pour la journée** — ✅ Ma journée (déroulé visuel)
**Pour le soir** — 🎁 Ma boîte à soucis

Le bouton « ⓘ Pour les parents » détaille l'intention clinique et la base scientifique de chaque jeu.

## Personnaliser le prénom
Ouvrir `index.html`, ligne ~ `const CHILD_NAME = "Alicia";` → remplacer par le prénom voulu.

## Héberger sur GitHub Pages (5 minutes)
1. Crée un dépôt GitHub (ex. `mon-petit-jardin`), **public**.
2. Téléverse **tous les fichiers de ce dossier** à la racine du dépôt
   (`index.html`, `manifest.webmanifest`, `sw.js`, les `.png`).
3. Dans le dépôt : **Settings → Pages**.
4. **Source : Deploy from a branch**, branche **main**, dossier **/ (root)**, puis **Save**.
5. Au bout d'une minute, l'adresse apparaît :
   `https://TON-PSEUDO.github.io/mon-petit-jardin/`
6. Envoie ce lien. Sur le téléphone, ouvrir le lien dans Safari/Chrome →
   menu **Partager → Sur l'écran d'accueil** : l'app s'installe comme une vraie application,
   fonctionne ensuite **sans connexion**.

Tout est statique : aucun serveur, aucune donnée envoyée. Les fiertés et le déroulé du jour
sont enregistrés **uniquement** dans le navigateur du téléphone (localStorage). La boîte à
soucis ne conserve rien, volontairement.
