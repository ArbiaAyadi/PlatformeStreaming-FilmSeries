# 🎬 Full-Stack Movie App – Angular 18 & Node.js

Ce projet est une application web complète de gestion de films développée avec **Angular 18** pour le frontend et **Node.js/Express** avec **MongoDB** pour le backend. Il propose une interface utilisateur réactive pour consulter les films et une API sécurisée pour l’authentification.

---

## 🧰 Technologies utilisées

### Frontend
- Angular 18
- TypeScript
- Tailwind CSS
- RxJS / HttpClient
- Pipes Angular (async, date, currency)
- Infinite scrolling

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Bcrypt.js (pour le hachage des mots de passe)
- CORS, Body-parser

---

## 🌐 Fonctionnalités

### 🎥 Frontend – Application Movie Angular 18
- Trois pages principales : **Accueil**, **Movies**, **Détails d’un film**
- Composants autonomes pour la **navbar** et le **footer**
- Trois sections de films : **Populaires**, **Les mieux notés**, **Actuellement au cinéma**
- Slider d’images de films
- **Défilement infini**
- **Cartes de films** avec titre, date de sortie et note
- Intégration d’une **API externe** pour récupérer les données des films
- Interface utilisateur **responsive** avec Tailwind CSS

👉 Tutoriel complet disponible [ici](https://techiediaries.com/angular-18-tutorial-httpclient-tailwind)

### 🔒 Backend – API Node.js/Express
- API REST simple avec route `/api/signup`
- Enregistrement d’utilisateur avec vérification d’unicité
- **Hashage des mots de passe** avec bcrypt
- Connexion à MongoDB locale via Mongoose
- Middleware CORS et body-parser

---

## ⚙️ Structure du projet

```bash
movie-app/
├── frontend/               # Application Angular 18
│   └── src/...
│
├── backend/                # Application Node.js/Express
│   ├── models/
│   │   └── User.js
│   ├── routes/
│   │   └── auth.js
│   ├── server.js
│   └── package.json


---

## 🚀 Installation & démarrage

### Prérequis
- Node.js & npm  
- Angular CLI  
- MongoDB local  

### Étapes

1. Cloner le dépôt :  
   ```bash
   git clone https://github.com/yourusername/PlateformeStreaming-FilmSeries.git

2. Backend :
cd PlateformeStreaming-FilmSeries/backend
npm install
npm start

3. Frontend :
cd ../frontend
npm install
ng serve

4. Ouvrir dans le navigateur :
http://localhost:4200

📄 Licence
Ce projet est sous licence MIT.
Voir le fichier LICENSE pour plus de détails.
