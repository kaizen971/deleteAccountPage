# PatrimoniScore - Page de Suppression de Compte

Page web pour permettre aux utilisateurs de l'application PatrimoniScore de faire une demande de suppression de compte, conforme aux exigences de Google Play Store et du RGPD.

## 🚀 Déploiement Rapide

### Option 1 : GitHub Pages (Recommandé)
1. Forkez ce repository
2. Allez dans Settings > Pages
3. Sélectionnez "Deploy from a branch"
4. Choisissez la branche `main` et le dossier `/ (root)`
5. Votre site sera disponible à : `https://votre-username.github.io/deleteAccountPage`

### Option 2 : Netlify
1. Connectez-vous à [Netlify](https://netlify.com)
2. Glissez-déposez le dossier du projet
3. Votre site sera déployé automatiquement

### Option 3 : Vercel
1. Connectez-vous à [Vercel](https://vercel.com)
2. Importez le repository GitHub
3. Déployez en un clic

## 📋 Fonctionnalités

- ✅ Formulaire de demande de suppression conforme RGPD
- ✅ Conformité Google Play Store
- ✅ Design responsive et moderne
- ✅ Validation en temps réel
- ✅ Gestion des états (loading, succès, erreur)
- ✅ Prêt pour intégration EmailJS

## 🔧 Configuration EmailJS

Pour activer l'envoi d'emails :

1. Créez un compte sur [EmailJS.com](https://www.emailjs.com/)
2. Créez un service email (Gmail, Outlook, etc.)
3. Créez un template d'email
4. Remplacez dans `index.html` :
   ```javascript
   'YOUR_SERVICE_ID' → Votre Service ID
   'YOUR_TEMPLATE_ID' → Votre Template ID  
   'YOUR_USER_ID' → Votre User ID
   ```

## 📱 Conformité

- **Google Play Store** : ✅ Conforme
- **RGPD** : ✅ Conforme
- **Accessibilité** : ✅ Conforme
- **Mobile** : ✅ Responsive

## 🛠️ Technologies

- HTML5
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (ES6+)
- EmailJS (optionnel)

## 📞 Contact

- **Email** : support@patrimoniscore.com
- **Délai de traitement** : Maximum 30 jours
- **Conformité** : RGPD et Google Play Store

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails. 