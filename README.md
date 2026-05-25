# Tableau de bord de présence des employés

Une application React moderne pour gérer et visualiser la présence des employés en temps réel.

## 🚀 Fonctionnalités

- 📊 **Dashboard complet** avec statistiques en temps réel
- 👥 **Gestion des employés** (12 employés de départ dans 8 départements)
- 📅 **Suivi quotidien** (31 jours de données générées automatiquement)
- 🔍 **Filtres avancés** par département, statut et type de congé
- 📈 **Graphiques interactifs** avec Recharts
- 📱 **Interface responsive** adaptée à tous les écrans
- 📤 **Export CSV** des données
- 🎨 **Design moderne** avec mode sombre premium
- ➕ **Ajout manuel** de nouvelles présences
- 🗑️ **Suppression** d'entrées existantes

## 🛠️ Technologies utilisées

- React 18
- Framer Motion (animations)
- Lucide React (icônes)
- Recharts (graphiques)
- Tailwind CSS (styling)
- Vite (build tool)

## 📥 Installation

### Option 1 : Version statique (recommandée)
Le fichier `dashboard.html` peut être ouvert directement dans n'importe quel navigateur moderne - aucune installation requise !

### Option 2 : Développement local
```bash
# Cloner le dépôt
git clone https://github.com/foriasser-hub/app-web-test.git
cd app-web-test

# Installer les dépendances
npm install

# Démarrer le serveur de développement
npm run dev

# OU pour une version de production
npm run build
npm run preview
```

## 🎯 Utilisation

1. **Ouvrir `dashboard.html`** dans votre navigateur
2. **Explorez les statistiques** dans le tableau de bord principal
3. **Utilisez les filtres** pour affiner la vue des données
4. **Ajoutez de nouvelles présences** via le formulaire dédié
5. **Exportez les données** en format CSV pour analyse

## 📁 Structure des fichiers

```
app-web-test/
├── dashboard.html          # Version HTML statique (prête à l'emploi)
├── index.html             # Version Vite (pour développement)
├── src/
│   ├── components/
│   │   └── EmployeeAttendanceApp.jsx  # Composant principal React
│   ├── App.jsx            # Point d'entrée React
│   ├── index.jsx          # Point de montage React
│   └── index.css          # Styles CSS
├── package.json           # Dépendances Node.js
├── vite.config.js         # Configuration Vite
├── README.md              # Documentation
└── dist/                  # Build de production
```

## 📊 Données incluses

L'application inclut des données de démonstration pour :
- **12 employés** répartis dans 8 départements (IT, Finance, RH, Marketing, Ventes, Opérations, Logistique, Service client, Achats)
- **31 jours** de présence (tout le mois de Mai 2026)
- **Statuts variés** : Présent, Absent, En retard
- **Types de congés** : Maladie, Congé annuel, Personnel, Casual
- **Heures supplémentaires** automatiquement calculées

## 🔧 Personnalisation

Pour modifier les données des employés, éditez le tableau `employees` dans le fichier `src/components/EmployeeAttendanceApp.jsx`.

Pour ajouter de nouveaux départements, modifiez le tableau `departments` dans le même fichier.

## 🌐 Déploiement en ligne

### Sur GitHub Pages
1. Accédez aux paramètres de votre dépôt GitHub
2. Naviguez vers "Pages" dans la sidebar
3. Sélectionnez la branche `main` comme source
4. Le site sera disponible sur `https://foriasser-hub.github.io/app-web-test`

### Sur Netlify / Vercel
- Drag & drop le dossier `dist` (production build)
- OU connectez directement votre dépôt GitHub

### Alternative simple
- Hébergez simplement le fichier `dashboard.html` sur n'importe quel serveur web

## 📝 License

Ce projet est open source et disponible sous [MIT License](LICENSE).

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
1. Fork le projet
2. Créer une branche (`git checkout -b feature/AmazingFeature`)
3. Commiter vos changements (`git commit -m 'Add AmazingFeature'`)
4. Pousser vers la branche (`git push origin feature/AmazingFeature`)
5. Ouvrir une Pull Request

## 🙏 Crédits

Développé avec ❤️ pour la gestion RH moderne.

---

🌟 **Star ce projet si vous le trouvez utile !** ⭐