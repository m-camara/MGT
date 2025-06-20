# 🎮 MGT 2025 – Major Gaming Tournament

Bienvenue sur le dépôt officiel de **MGT 2025**, un site vitrine événementiel pour un tournoi de versus fighting à Shibuya. Ce projet est une réalisation HTML/CSS avec intégration de Bootstrap, centrée sur l'accessibilité, la performance et le responsive design.

---

## 🌐 Aperçu du site

- **Page d'accueil** (`index.html`) : Présente l'événement.
- **Accueil** (`accueil.html`) : Mise en avant des sections clés du tournoi (Cosplay, All Star, Contact).
- **Programme** (`programme.html`) : Détail complet des événements et activités.
- **Contact** (`contact.html`) : Présentation de Kayane + formulaire de participation.

---

## 🛠️ Technologies utilisées

- HTML5
- CSS3
- Bootstrap 5.3
- Responsive design via media queries
- Hébergement des médias sur [PostImg.cc](https://postimg.cc/)

---

## 📋 Structure du projet

```
/
├── index.html
├── accueil.html
├── programme.html
├── contact.html
├── style.css               # Style global et accueil
├── stylz.css               # Style spécifique pour accueil.html
├── programme-style.css     # Style spécifique pour programme.html
├── contact.css             # Style spécifique pour contact.html
```

---

## 📱 Responsive Design

✅ Compatibilité testée sur plusieurs résolutions :
- Mobile (425px)
- Tablette (768px)
- Desktop (1920px)

Utilisation extensive de media queries pour garantir une expérience optimale sur tous les formats d’écran.

---

## 🚦 Scores Lighthouse

Des audits Lighthouse ont été réalisés sur chaque page (desktop & mobile) :

| Page         | Performance | Accessibilité | SEO | Best Practices |
|--------------|-------------|----------------|-----|----------------|
| `index.html` | 60–70       | 85+            | ✅  | ✅              |
| `accueil.html` | 50–65 (mobile) | 80+       | ✅  | ⚠️ quelques scripts |
| `programme.html` | ~55     | 75+            | ✅  | ⚠️ lazy loading absent |
| `contact.html` | ~60       | ✅ (90+)        | ✅  | ⚠️ formulaire à améliorer |

**Principales recommandations :**
- Optimisation des images (WebP, compression)
- Mise en place de `loading="lazy"` sur les balises `<img>`
- Ajout d’attributs `alt`, `label`, `aria-*` pour l’accessibilité
- Réduction des gaps en `rem` sur la navigation pour les petits écrans

---

## ♿ Accessibilité – Audit WebAIM/WAVE

Analyse WAVE effectuée :

- ✅ Bon contraste global
- ⚠️ Champs de formulaire sans `for`/`id` cohérents
- ⚠️ `id` en doublon (`name` utilisé plusieurs fois)
- ✅ Navigation clavier fonctionnelle
- ✅ Texte alternatif présent sur la majorité des images

**Axes d’amélioration :**
- Associer les `label` à des `input` uniques
- Corriger les `id` dupliqués
- Ajouter un focus visible sur les éléments interactifs

---

## 📥 Installation locale

```bash
git clone https://github.com/votre-utilisateur/mgt2025.git
cd mgt2025
# Ouvrir index.html dans votre navigateur
```

---

## 📸 Capture d'écran

| <img width="212" alt="mobile accueil mgt" src="https://github.com/user-attachments/assets/5ef97e77-42ae-48fe-8329-4d63931da2dc" /> | <img width="212" alt="contact mobile " src="https://github.com/user-attachments/assets/b9a2346c-73d1-4f02-ae7d-3aed725316dd" />|
|:--:|:--:|
| Accueil (desktop) | Formulaire (mobile) |

---

## 🔧 À venir

- Ajout de JavaScript pour validation du formulaire
- Accessibilité niveau WCAG 2.1 AA
- Ajout d’une section galerie ou “à propos”

---


## 🧑‍💻 Auteur

**[Mohamed Camara]** – Développeur junior.

---
🔧 Scores Lighthouse en format Mobile et Ordinateur et Webaim
---
<img width="269" alt="programmehtmllighthouse" src="https://github.com/user-attachments/assets/39677252-bd1c-48de-9a84-b104c9f380b2" />
<img width="271" alt="programme html lightouse" src="https://github.com/user-attachments/assets/5c1fd734-4d82-4d62-a21a-4252a6c35403" />
<img width="271" alt="index htmllighthouse" src="https://github.com/user-attachments/assets/51d6e268-e440-4558-85b1-1509d3e74a12" />
<img width="269" alt="index html lighthouse" src="https://github.com/user-attachments/assets/60d4a283-2d16-470d-a45e-50cde57eeea9" />
<img width="268" alt="contacthtmllighthousemobile" src="https://github.com/user-attachments/assets/d0b54322-0ecc-45d2-8f4f-099f3413881b" />
<img width="272" alt="contact htmllighthouse" src="https://github.com/user-attachments/assets/eeabdad3-ca99-43fc-96bb-e1303b404dc2" />
<img width="269" alt="accueilhtmlmobilelighthouse" src="https://github.com/user-attachments/assets/d97e4469-a94b-4750-94e1-8ab307e9565a" />
<img width="269" alt="accueilhtmllighthouse" src="https://github.com/user-attachments/assets/83728e5a-3b54-480a-847b-ef2ceb62e3ac" />
<img width="387" alt="webaim note" src="https://github.com/user-attachments/assets/2d897153-cd1e-4ad4-9071-84f321018d59" />
