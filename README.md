# Veille Legaltech et Produit

Page web de la newsletter de Victor Soussan. Le fichier `index.html` contient l'édition du 28 septembre au 4 octobre 2026.

## Déploiement sur Vercel

1. Dans Vercel, crée un projet et importe ce dépôt GitHub.
2. Choisis le framework **Other**.
3. Laisse la commande de build vide et utilise la racine du dépôt comme répertoire de sortie.
4. Déploie le projet. Vercel fournira l'URL publique à utiliser dans le lien « Lire dans le navigateur » de l'e-mail.

Le site est statique : chaque nouvelle édition remplace `index.html`. Un push sur la branche de production déclenchera ensuite un nouveau déploiement si le dépôt reste relié au projet Vercel.
