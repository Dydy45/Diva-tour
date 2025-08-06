# NaturalGlow - Site E-commerce de Cosmétiques Naturels

Un site web professionnel et moderne pour une marque de cosmétiques naturels et biologiques.

## 🌟 Fonctionnalités

### Pages principales
- **Accueil** (`index.html`) - Page d'accueil avec hero section, produits phares et témoignages
- **Produits** (`products.html`) - Catalogue complet avec filtres, recherche et tri
- **À propos** (`about.html`) - Histoire de l'entreprise, équipe et valeurs
- **Contact** (`contact.html`) - Formulaire de contact et FAQ
- **Détail produit** (`detail-product.html`) - Page détaillée pour chaque produit

### Fonctionnalités techniques
- **Design responsive** - Compatible mobile, tablette et desktop
- **Navigation dynamique** - Menu déroulant et navigation fluide
- **Panier interactif** - Gestion du panier avec localStorage
- **Filtres produits** - Recherche, tri et filtrage par catégories
- **Animations CSS** - Effets de hover et transitions fluides
- **SEO optimisé** - Meta tags et structure sémantique

## 🎨 Design

### Palette de couleurs
- **Primaire** : `#5C3A21` (Marron naturel)
- **Secondaire** : `#7a4c2e` (Marron clair)
- **Fond clair** : `#F8F5F1` (Beige doux)
- **Fond blanc** : `#FFFDFB` (Blanc cassé)
- **Fond doux** : `#f2eae4` (Beige rosé)

### Typographie
- **Police principale** : Segoe UI, sans-serif
- **Style** : Moderne et épuré avec des accents naturels

## 🛠️ Technologies utilisées

- **HTML5** - Structure sémantique moderne
- **CSS3** - Styles avec variables CSS et Flexbox/Grid
- **Bootstrap 5.3** - Framework CSS responsive
- **Bootstrap Icons** - Icônes vectorielles
- **JavaScript ES6** - Interactivité et gestion d'état
- **LocalStorage** - Persistance des données côté client

## 📱 Responsive Design

Le site s'adapte automatiquement à tous les formats d'écran :
- **Mobile** : < 576px
- **Tablette** : 576px - 992px  
- **Desktop** : > 992px

## 🚀 Installation et utilisation

1. **Cloner le projet**
   ```bash
   git clone [url-du-repo]
   cd naturalglow
   ```

2. **Ouvrir le site**
   - Ouvrez `index.html` dans votre navigateur
   - Ou utilisez un serveur local pour de meilleures performances

3. **Serveur de développement** (optionnel)
   ```bash
   # Avec Python
   python -m http.server 8000
   
   # Avec Node.js
   npx serve .
   ```

## 📁 Structure du projet

```
naturalglow/
│
├── index.html              # Page d'accueil
├── products.html           # Catalogue produits
├── about.html              # À propos
├── contact.html            # Contact
├── detail-product.html     # Détail produit
│
├── css/
│   └── style.css           # Styles principaux
│
├── images/                 # Ressources visuelles
│   ├── logo-naturalglow.png
│   ├── hero-bg.jpg
│   ├── products/           # Images produits
│   └── team/              # Photos équipe
│
└── README.md              # Documentation
```

## 🎯 Fonctionnalités du panier

- **Ajout de produits** - Avec gestion des quantités
- **Persistance** - Sauvegarde dans localStorage
- **Compteur dynamique** - Affichage du nombre d'articles
- **Gestion des doublons** - Mise à jour des quantités

## 🔍 Fonctionnalités de recherche

- **Recherche textuelle** - Dans les noms et descriptions
- **Filtres par catégorie** - Visage, Corps, Cheveux
- **Tri dynamique** - Par nom, prix, note
- **URL paramétrable** - Support des liens directs

## 📊 Performance et SEO

### Optimisations techniques
- **Images optimisées** - Lazy loading et compression
- **CSS/JS minifiés** - Chargement rapide
- **Cache browser** - Ressources mises en cache
- **Structure sémantique** - HTML5 valide

### SEO
- **Meta descriptions** - Pages optimisées pour les moteurs
- **Open Graph** - Partage sur réseaux sociaux
- **Schema markup** - Données structurées
- **URLs propres** - Navigation claire

## 🛡️ Sécurité

- **Validation côté client** - Formulaires sécurisés
- **Sanitisation** - Protection XSS
- **HTTPS ready** - Compatible SSL/TLS

## 📞 Support

Pour toute question ou suggestion :
- **Email** : contact@naturalglow.fr
- **Téléphone** : +33 1 23 45 67 89

## 📝 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
1. Fork le projet
2. Créer une branche feature
3. Commiter vos changements
4. Pousser vers la branche
5. Ouvrir une Pull Request

---

**NaturalGlow** - Beauté naturelle, éclat authentique ✨
