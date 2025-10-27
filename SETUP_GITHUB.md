# 🚀 Instructions pour créer le dépôt GitHub

## Étape 1 : Créer le dépôt sur GitHub

1. Allez sur [github.com](https://github.com) et connectez-vous
2. Cliquez sur le bouton **"+"** en haut à droite, puis **"New repository"**
3. Nommez le dépôt : `kavcom` (ou un autre nom de votre choix)
4. **Ne cochez PAS** "Initialize this repository with a README"
5. Cliquez sur **"Create repository"**

## Étape 2 : Connecter le dépôt local

Copiez-collez ces commandes dans votre terminal :

```bash
cd "/Users/codenolimits-dreamai-nanach/Desktop/DREAM NOVA INVEST"

# Ajoutez le remote GitHub (remplacez VOTRE-USERNAME par votre username)
git remote add origin https://github.com/VOTRE-USERNAME/kavcom.git

# Renommez la branche en main (si nécessaire)
git branch -M main

# Poussez le code
git push -u origin main
```

## ✅ C'est fait !

Votre site est maintenant sur GitHub à l'adresse :
`https://github.com/VOTRE-USERNAME/kavcom`

## 🌐 Déployer le site (Optionnel)

### Option 1 : GitHub Pages (Gratuit)

1. Allez dans **Settings** > **Pages**
2. Sélectionnez la branche **main** dans "Source"
3. Cliquez sur **Save**
4. Votre site sera disponible à : `https://VOTRE-USERNAME.github.io/kavcom/`

### Option 2 : Netlify (Gratuit)

1. Allez sur [netlify.com](https://netlify.com)
2. Glissez-déposez le dossier du projet
3. Le site sera déployé instantanément !

### Option 3 : Vercel (Gratuit)

1. Allez sur [vercel.com](https://vercel.com)
2. Connectez votre dépôt GitHub
3. Déployez en un clic !

---

**Note importante** : N'oubliez pas de modifier l'URL de redirection dans `index.html` ligne 197 :

```html
<input type="hidden" name="_next" value="https://VOTRE-DOMAINE/merci.html">
```

Remplacez `[VOTRE-DOMAINE]` par l'URL réelle de votre site déployé.

