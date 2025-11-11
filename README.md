# Je vends mon VE - Landing Page

Landing page moderne pour une plateforme de mise en relation entre particuliers pour l'achat et la vente de véhicules électriques.

## 📋 Fonctionnalités

- Design moderne et responsive (desktop, tablette, mobile)
- Formulaire de contact fonctionnel avec Web3Forms
- Intégration des réseaux sociaux (Facebook, Instagram)
- Animations fluides et interface intuitive
- Couleur d'accent personnalisée (#4ecc8b)

## 🚀 Installation

1. Clonez ce dépôt
2. Ajoutez votre logo (voir section Logo ci-dessous)
3. Configurez le formulaire de contact (voir section Formulaire ci-dessous)
4. Mettez à jour les liens des réseaux sociaux
5. Ouvrez `index.html` dans votre navigateur

## 🖼️ Logo

### Où placer le logo
Placez votre fichier logo à la racine du projet.

### Nom du fichier
Le fichier doit s'appeler : **`logo.png`**

### Format recommandé
- Format : PNG avec fond transparent
- Dimensions : 200-300px de largeur
- Le logo sera automatiquement redimensionné

Le logo apparaîtra :
- Dans le header (hauteur 50px sur desktop, 40px sur mobile)
- Dans le footer (hauteur 40px, en blanc)

## 📧 Configuration du formulaire de contact

Le formulaire utilise **Web3Forms**, un service gratuit pour envoyer des emails sans backend.

### Étape 1 : Créer un compte Web3Forms

1. Allez sur [https://web3forms.com](https://web3forms.com)
2. Cliquez sur "Get Started" ou "Create Access Key"
3. Entrez votre email
4. Vous recevrez une clé d'accès (Access Key)

### Étape 2 : Configurer la clé

Dans le fichier `index.html`, trouvez la ligne 158 :

```html
<input type="hidden" name="access_key" value="YOUR_ACCESS_KEY_HERE">
```

Remplacez `YOUR_ACCESS_KEY_HERE` par votre clé d'accès Web3Forms.

### Exemple
```html
<input type="hidden" name="access_key" value="abcd1234-efgh-5678-ijkl-9012mnop3456">
```

### Test du formulaire

Une fois la clé configurée :
1. Ouvrez `index.html` dans votre navigateur
2. Remplissez le formulaire
3. Cliquez sur "M'inscrire à la newsletter"
4. Vous devriez recevoir un email avec les informations du formulaire

## 🔗 Réseaux sociaux

Mettez à jour les liens des réseaux sociaux dans `index.html` :

### Dans le header (lignes 21 et 26)
```html
<a href="https://facebook.com/votre-page" ...>
<a href="https://instagram.com/votre-compte" ...>
```

### Dans le footer (lignes 197 et 202)
```html
<a href="https://facebook.com/votre-page" ...>
<a href="https://instagram.com/votre-compte" ...>
```

## 🎨 Personnalisation des couleurs

Pour changer la couleur d'accent, modifiez les variables CSS dans `styles.css` (lignes 11-13) :

```css
--primary-color: #4ecc8b;  /* Couleur principale */
--primary-dark: #2a9d63;   /* Couleur foncée */
--primary-light: #6dd9a4;  /* Couleur claire */
```

## 📱 Responsive

La page est entièrement responsive avec des breakpoints pour :
- Desktop : > 1024px
- Tablette : 768px - 1024px
- Mobile : 480px - 768px
- Petit mobile : 360px - 480px
- Très petit mobile : < 360px

## 🛠️ Technologies utilisées

- HTML5
- CSS3 (Flexbox, Grid, Variables CSS)
- JavaScript (ES6+, Fetch API)
- Web3Forms pour l'envoi d'emails
- Google Fonts (Inter)

## 📝 Structure des fichiers

```
monve/
├── index.html          # Page HTML principale
├── styles.css          # Styles CSS
├── logo.png           # Logo (à ajouter)
└── README.md          # Ce fichier
```

## ⚡ Performance

- Police web optimisée avec Google Fonts
- SVG pour les icônes (léger et scalable)
- CSS minimaliste et optimisé
- Pas de dépendances externes (sauf fonts)

## 🌐 Déploiement

Pour déployer la page :

### Sur GitHub Pages
1. Poussez les fichiers sur GitHub
2. Allez dans Settings > Pages
3. Sélectionnez la branche principale
4. Votre site sera disponible sur `username.github.io/monve`

### Sur Netlify
1. Créez un compte sur Netlify
2. Glissez-déposez le dossier du projet
3. Votre site sera en ligne en quelques secondes

### Sur Vercel
1. Créez un compte sur Vercel
2. Importez le projet depuis GitHub
3. Déployez automatiquement

## 📞 Support

Pour toute question ou problème :
- Vérifiez que votre clé Web3Forms est correctement configurée
- Assurez-vous que le fichier logo.png existe
- Testez dans différents navigateurs
- Vérifiez la console JavaScript pour les erreurs

## 📄 Licence

Ce projet est sous licence libre. Vous pouvez l'utiliser et le modifier comme bon vous semble.
