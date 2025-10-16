# BMDATA_Blog-tFileOutputPDF2


Ce projet de démonstration illustre l’utilisation du composant communautaire **tFileOutputPDF2**
pour générer automatiquement un fichier PDF à partir de données Talend.

## 🧩 Structure

- **tRowGenerator** → génération de données fictives  
- **tMap** → enrichissement des colonnes (total panier, utilisateur enregistré)  
- **tFileOutputPDF2** → génération du fichier PDF final  

## ⚙️ Contexte à renseigner

Avant d’exécuter le job, définissez ces trois variables de contexte :

| Variable | Description |
|-----------|-------------|
| `sDossier_OUTPUT` | Dossier de sortie du fichier PDF |
| `sCheminFichier_LOGO` | Chemin du logo à insérer dans le rapport |
| `sCheminFichier_SIGNATURE` | Chemin de la signature à insérer |

## 💡 Note

Ce job est conçu pour **Talend Open Studio 7.3.x** et **Talaxie**.  
Il est entièrement autonome et ne nécessite aucune base de données.

Documentation complète sur : [https://bmdata.fr/blog/tFIleOutputPDF2/](https://bmdata.fr/blog/tFIleOutputPDF2/)

---
© 2025 BM Data — Démonstration technique Talend
