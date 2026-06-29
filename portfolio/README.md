# Portfolio — Anas Louraibi
**BUT Réseaux & Télécommunications · Parcours Cybersécurité · IUT d'Aubière**

Portfolio personnel présentant mon parcours, mes compétences et mon expérience de stage chez Hutchinson.

---

## 🚀 Lancer en local

Pas de framework, pas de build — juste un fichier HTML.

```bash
# Option 1 : ouvrir directement dans le navigateur
open index.html     # macOS
start index.html    # Windows

# Option 2 : serveur local (recommandé pour éviter les problèmes CORS)
python -m http.server 8080
# puis ouvrir http://localhost:8080
```

---

## 📁 Structure du projet

```
portfolio/
├── index.html          # Portfolio complet (tout-en-un)
├── anas.jpeg           # Photo de profil
├── Cv_Alternances.pdf  # CV au format PDF
└── README.md
```

> **Note :** Le portfolio est un fichier HTML unique (CSS et JS inclus).
> Aucune dépendance externe à installer.

---

## 🌐 Publier sur GitHub Pages

### Étape 1 — Créer le repository GitHub

1. Aller sur [github.com](https://github.com) et se connecter
2. Cliquer sur **New repository** (bouton vert en haut à droite)
3. Nommer le repo : `portfolio` (ou `PortfolioStage2026`)
4. Laisser en **Public**
5. Ne pas cocher "Add a README" (on a déjà le nôtre)
6. Cliquer **Create repository**

### Étape 2 — Envoyer les fichiers sur GitHub

```bash
# Depuis le dossier du portfolio :
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
git remote add origin https://github.com/TON_USERNAME/portfolio.git
git push -u origin main
```

> Remplacer `TON_USERNAME` par ton nom d'utilisateur GitHub.

### Étape 3 — Activer GitHub Pages

1. Dans le repository GitHub, aller dans **Settings** → **Pages**
2. Sous "Source", sélectionner **Deploy from a branch**
3. Choisir la branche **main** et le dossier **/ (root)**
4. Cliquer **Save**

### Étape 4 — Récupérer le lien public

Après quelques minutes, GitHub génère l'URL :
```
https://TON_USERNAME.github.io/portfolio/
```

Ce lien est à partager sur ton CV, LinkedIn et en entretien.

---

## ✏️ Personnaliser le portfolio

### Changer la photo
Remplacer le fichier `anas.jpeg` par ta nouvelle photo (garder le même nom ou adapter la référence dans `index.html`).

### Mettre à jour le CV
Remplacer `Cv_Alternances.pdf` par la nouvelle version.

### Modifier du contenu
Tout le contenu est dans `index.html`. Rechercher les sections par leur commentaire :
- `<!-- HERO -->` → accroche principale
- `<!-- À PROPOS -->` → présentation
- `<!-- FORMATION -->` → parcours scolaire
- `<!-- EXPÉRIENCES -->` → expériences pro
- `<!-- COMPÉTENCES -->` → skills techniques
- `<!-- PROJETS -->` → projets SAÉ
- `<!-- DIVERS -->` → loisirs et langues
- `<!-- CONTACT -->` → coordonnées

### Changer la couleur d'accentuation
Dans le `<style>`, modifier `--amber: #f0a500;` par la couleur souhaitée.

---

## 📤 Mettre à jour le portfolio en ligne

```bash
git add .
git commit -m "Mise à jour portfolio"
git push
```

GitHub Pages se met à jour automatiquement en quelques secondes.

---

## 🔧 Technologies utilisées

| Élément | Choix |
|---------|-------|
| Structure | HTML5 pur — aucun framework |
| Style | CSS variables + animations natives |
| Interactivité | JavaScript vanilla |
| Polices | Inter + JetBrains Mono (Google Fonts) |
| Hébergement | GitHub Pages |

---

*Anas Louraibi · 2026 · IUT d'Aubière — Université Clermont Auvergne*
