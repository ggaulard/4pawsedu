# 📸 Guide des images du site

Ce document liste toutes les images utilisées sur le site web 4 Paws'itive Education.

## 📁 Structure

Toutes les images sont stockées dans `/src/images/`

## 🖼️ Liste des images

### Page d'accueil (index.html)

| Image | Nom du fichier | Utilisation | Dimensions |
|-------|---------------|-------------|------------|
| Border Collie | `hero-dog-1.jpg` | Section hero - Image circulaire gauche | 200x200px (rond) |
| Chien blanc | `hero-dog-2.jpg` | Section hero - Image circulaire droite | 200x200px (rond) |
| Chien extérieur | `welcome-dog.jpg` | Section introduction | 400x400px |
| Chien portrait | `about-intro.jpg` | Section "À propos" (preview) | 350x350px |

### Page Services (services.html)

| Image | Nom du fichier | Utilisation | Dimensions |
|-------|---------------|-------------|------------|
| Chien Shiba | `service-bilan.jpg` | Bilan comportemental | 400x400px |
| Chien noir | `service-cours.jpg` | Cours d'éducation | 400x400px |
| Chiens labradors | `service-promenade.jpg` | Service promenade | 400x400px |
| Chiot | `service-adoption.jpg` | Accompagnement pré-adoption | 400x400px |

### Page À propos (apropos.html)

| Image | Nom du fichier | Utilisation | Dimensions |
|-------|---------------|-------------|------------|
| Portrait Angelina | `angelina-profile.jpg` | Photo de profil d'Angelina | 300x400px |
| Chiens neige | `formation-dogs.jpg` | Section formations | 400x400px |

### Autres

| Image | Nom du fichier | Utilisation | Dimensions |
|-------|---------------|-------------|------------|
| Logo | `logo.jpg` | Logo du site (non utilisé actuellement) | Variable |

## 🎨 Style des images

### Hero Images (Cercles)
- Bordure blanche de 5px
- Ombre portée
- Effet hover: agrandissement + rotation
- Disposition: côte à côte (desktop) / colonne (mobile)

### Images de contenu
- Border-radius: 20px (coins arrondis)
- Box-shadow: ombre douce
- Object-fit: cover (recadrage automatique)
- Responsive: hauteur adaptative sur mobile

### Layout
- **Desktop**: Images à côté du texte (grid 2 colonnes)
- **Tablette**: Images réduites
- **Mobile**: Images empilées au-dessus du texte

## 📱 Responsive

### Desktop (> 768px)
- Images hero: 200x200px
- Images contenu: 300-400px de largeur
- Layout grid avec texte à côté

### Mobile (< 768px)
- Images hero: 150x150px
- Images contenu: 100% largeur, hauteur 300px
- Layout empilé vertical

## 🔄 Ordre des images (mobile)

Pour la page services, l'ordre change sur mobile pour améliorer la lisibilité :
1. Image en haut
2. Texte en dessous

## ✅ Checklist d'intégration

- [x] 11 images extraites et copiées
- [x] HTML mis à jour sur toutes les pages
- [x] CSS ajouté pour styliser les images
- [x] Responsive design implémenté
- [x] Effets hover ajoutés
- [x] Alt text descriptif pour l'accessibilité

## 🚀 Pour tester

Lancez le serveur de développement :
```bash
npm start
```

Et visitez :
- http://localhost:3000/index.html - Page d'accueil
- http://localhost:3000/services.html - Services
- http://localhost:3000/apropos.html - À propos

---

**Note**: Toutes les images proviennent du site original exporté depuis `/ressources/exports/`

