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

## ⚙️ Installation rapide du projet dans Talend / Talaxie

Ce projet peut être importé en quelques minutes dans **Talend Open Studio** ou **Talaxie**.

### Étapes à suivre

1. **Créer un nouveau projet**
   - Lancez Talend (ou Talaxie).
   - Créez un projet vide, par exemple : `PDF_DEMO_PROJECT`.

2. **Télécharger l’archive ZIP du projet**
   - Depuis GitHub :  
     [BMDATA_Blog-tFileOutputPDF2.zip](https://github.com/mbodetdata/BMDATA_Blog-tFileOutputPDF2/archive/refs/heads/main.zip)

3. **Extraire l’archive ZIP**
   - Décompressez le fichier sur votre poste (ex. `C:\Talend\PDF_Demo\`).

4. **Remplacer les dossiers du projet**
   - Copiez les dossiers suivants du ZIP :
     ```
     process/
     code/
     ```
   - Collez-les dans votre projet **nouvellement créé** (même arborescence).
   - Confirmez le remplacement des fichiers existants.

5. **Rafraîchir le Studio Talend**
   - Dans Talend, clic droit sur votre projet → **Rafraîchir**.
   - Les jobs et routines apparaîtront automatiquement.

6. **Récupérer les fichiers d’entrée**
   - Les exemples de données sont dans le dossier :
     ```
     FICHIER_IN/
     ```
   - Copiez ce dossier à l’endroit de votre choix (ou laissez-le dans le projet).

---

✅ **Le projet est prêt !**
Vous pouvez maintenant :
- Ouvrir le job principal,  
- Renseigner les variables de contexte (logo, signature, dossier de sortie),  
- Et exécuter le flux complet pour générer votre premier **PDF automatique Talend**.

---


© 2025 BM Data — Démonstration technique Talend
