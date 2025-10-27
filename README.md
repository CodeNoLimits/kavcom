# 🌡️ KavCom - Solutions de Chauffage & Climatisation

Site web moderne pour les solutions de chauffage et climatisation en France.

## 🎯 Fonctionnalités

- ✅ Design moderne et responsive
- ✅ Formulaire de contact avec envoi d'emails automatique
- ✅ Page de remerciement
- ✅ Couleur verte (emerald) moderne
- ✅ Compatible mobile et desktop

## 📧 Configuration Email

Le formulaire envoie automatiquement les emails à :
- **David** : admin@holyrentals.com (destinataire principal)
- **Ariel** : bariel@hotmail.fr (copie automatique)

Utilise [FormSubmit](https://formsubmit.co) pour l'envoi d'emails sans API.

## 🚀 Installation

1. Clonez le dépôt :
```bash
git clone https://github.com/[VOTRE-USERNAME]/kavcom.git
cd kavcom
```

2. Ouvrez `index.html` dans votre navigateur

## 📁 Structure du Projet

```
kavcom/
├── index.html      # Page d'accueil avec formulaire
├── merci.html      # Page de confirmation
└── README.md       # Documentation
```

## 🎨 Couleurs Utilisées

- **Emerald 50** : `#ecfdf5` - Fond clair
- **Emerald 600** : `#059669` - Boutons principaux
- **Emerald 700** : `#047857` - Hover
- **Emerald 900** : `#064e3b` - Texte foncé

## 📝 Champs du Formulaire

- Nom complet (requis)
- Email (requis)
- Téléphone (requis)
- Type de chauffage actuel
- Message (optionnel)

## ⚙️ Configuration FormSubmit

Les configurations suivantes sont définies dans le formulaire :
- Template en tableau pour un affichage propre
- Auto-réponse au client
- Protection anti-spam (honey pot)
- Désactivation de reCAPTCHA

## 🔧 Personnalisation

Pour modifier l'URL de redirection après envoi, éditez cette ligne dans `index.html` :

```html
<input type="hidden" name="_next" value="https://[VOTRE-DOMAINE]/merci.html">
```

Remplacez `[VOTRE-DOMAINE]` par votre domaine réel.

## 🌐 Déploiement

### GitHub Pages

1. Poussez le code sur GitHub
2. Allez dans Settings > Pages
3. Sélectionnez la branche main
4. Le site sera disponible à : `https://[USERNAME].github.io/kavcom`

### Netlify / Vercel

- Drag & drop du dossier ou connexion à GitHub
- Déploiement automatique

## 📱 Responsive

Le site est entièrement responsive et s'adapte à :
- Mobiles (320px+)
- Tablettes (768px+)
- Desktop (1024px+)

## ✅ Checklist de Test

- [ ] Formulaire fonctionne
- [ ] Email arrive bien à David
- [ ] Copie envoyée à Ariel
- [ ] Redirection vers merci.html
- [ ] Auto-réponse envoyée au client
- [ ] Responsive sur mobile
- [ ] Tous les liens fonctionnent

## 📞 Contact

Pour toute question ou support, contactez :
- Email : contact@kavcom.fr
- Téléphone : 0800 000 000

---

**Créé avec ❤️ par KavCom Team**

