

---

L'Horloge Éternelle (The Eternal Clock)

Description

Une horloge analogique interactive et artistique qui simule les effets de lumière naturelle selon l'heure de la journée. Le projet combine un design vintage de musée avec des effets d'éclairage dynamiques et des sons mécaniques authentiques.

Fonctionnalités

· 🕐 Horloge analogique en temps réel avec aiguilles animées
· ☀️ Simulation de la lumière solaire et des ombres selon l'heure
· 🌙 Transition automatique jour/nuit avec éclairage ambiant
· 🔊 Sons de tic-tac mécaniques via Web Audio API
· 🔔 Carillon spécial à midi et minuit
· ⏱️ Compteur de jours d'activité du site (uptime)
· 🎨 Design vintage avec texture de bruit et effets de profondeur
· 📱 Interface responsive (mobile et desktop)
· ✨ Effets d'ombre dynamiques sur le boîtier

Technologies Utilisées

· HTML5 Canvas (dessin de l'horloge)
· CSS3 (variables, animations, filtres, mix-blend-mode)
· JavaScript vanilla
· Web Audio API (génération de sons)
· Google Fonts (Great Vibes, Playfair Display, Montserrat)

Fonctionnement

Calcul de la Lumière

· La position du soleil est calculée selon l'heure locale
· Les ombres se déplacent naturellement tout au long de la journée
· L'intensité lumineuse varie entre le jour et la nuit

Système Audio

· Sons de tic-tac générés à chaque seconde
· Carillon mélodique aux changements d'heure
· Activation audio sur première interaction utilisateur

Compteur de Jours

· Affiche le nombre de jours depuis le déploiement
· Date de référence : 21 août 2026

Personnalisation

Modifier la Date de Départ

```javascript
const START_DATE = new Date('2026-08-21T00:00:00');
```

Modifier le Nom de la Marque

```javascript
ctx.fillText('clockMC88', center, center - 150);
```

Modifier l'Email de Contact

```javascript
ctx.fillText('mohamed005cheikh@gmail.com', center, center + 160);
```

Structure du Code

· HTML : Structure de base avec canvas et compteur
· CSS : Styles, variables d'éclairage, effets visuels
· JavaScript :
  · Gestion du temps et des calculs d'éclairage
  · Rendu du canvas (aiguilles, chiffres, graduations)
  · Génération audio (tic-tac et carillons)
  · Animation en boucle avec requestAnimationFrame

Installation

Aucune installation requise. Il suffit d'ouvrir le fichier HTML dans un navigateur moderne.

Compatibilité

· Chrome, Firefox, Safari, Edge (versions récentes)
· Nécessite JavaScript activé
· Web Audio API requise pour les sons

Contact

· Email : mohamed005cheikh@gmail.com
· Marque : clockMC88

---

Souhaitez-vous que je crée un README pour un autre code ?
