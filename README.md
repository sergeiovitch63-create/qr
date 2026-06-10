# QR Code dynamique (gratuit, via GitHub Pages)

Ce petit site fait une seule chose : **rediriger automatiquement** toute personne
qui scanne votre QR code vers l'adresse de votre choix.

## 💡 Le principe

- Votre QR code imprimé pointe vers une adresse **fixe** (votre site GitHub Pages).
- Cette page redirige instantanément le visiteur vers la **vraie destination**.
- Pour changer la destination, vous modifiez **une seule ligne** dans ce dépôt.

> ✅ **Le QR code imprimé ne change JAMAIS.**
> Seule la destination de la redirection change. Vous pouvez donc imprimer
> votre QR code une bonne fois pour toutes (affiches, cartes de visite, menus...)
> et changer la page de destination autant de fois que vous voulez, gratuitement.

## ✏️ Comment changer la destination

Tout se passe dans le fichier `index.html`, directement depuis le site GitHub
(pas besoin d'installer quoi que ce soit).

### Étape 1 — Ouvrir le fichier

1. Allez sur la page de votre dépôt GitHub (le projet qui contient ces fichiers).
2. Cliquez sur le fichier **`index.html`** dans la liste des fichiers.
3. Cliquez sur l'icône **crayon ✏️** (en haut à droite du fichier) pour passer en mode édition.

### Étape 2 — Modifier la ligne de destination

Cherchez, vers le haut du fichier, le bloc bien visible :

```html
<!-- ============================================================ -->
<!-- ⚠️  DESTINATION DU QR CODE — LA SEULE LIGNE À MODIFIER  ⚠️   -->
<!-- ============================================================ -->
<meta http-equiv="refresh" content="0; url=https://example.com">
```

Remplacez uniquement l'adresse après `url=`. Par exemple, pour rediriger vers
votre page Instagram :

```html
<meta http-equiv="refresh" content="0; url=https://www.instagram.com/moncompte/">
```

⚠️ Ne touchez à rien d'autre : gardez bien les guillemets, le `0;` et le `url=`.

### Étape 3 — Enregistrer (« commit ») le changement

1. Cliquez sur le bouton vert **« Commit changes... »** en haut à droite.
2. Une petite fenêtre s'ouvre : vous pouvez laisser le message proposé tel quel
   (ou écrire par exemple « Nouvelle destination »).
3. Laissez l'option **« Commit directly to the main branch »** cochée.
4. Cliquez sur le bouton vert **« Commit changes »**.

C'est tout ! 🎉

### Étape 4 — Patienter une ou deux minutes

GitHub Pages met généralement **1 à 2 minutes** à publier le changement.
Ensuite, toute personne qui scanne votre QR code arrivera sur la nouvelle adresse.

## ❓ Questions fréquentes

**Dois-je réimprimer mon QR code après un changement ?**
Non, jamais. Le QR code pointe toujours vers la même adresse (votre site
GitHub Pages). C'est la redirection qui change, pas le QR.

**Le changement ne semble pas pris en compte ?**
Attendez 2-3 minutes, puis réessayez. Si votre téléphone affiche encore
l'ancienne page, c'est peut-être le cache du navigateur : fermez l'onglet
et rescannez le QR code.

**Combien ça coûte ?**
Rien. GitHub et GitHub Pages sont gratuits pour ce type d'usage.
**Combien ça coûte ?**
Rien. GitHub et GitHub Pages sont gratuits pour ce type d'usage.
