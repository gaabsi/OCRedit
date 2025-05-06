# OCRédit 

## Projet alliant scoring crédit OCR et utilisation de LLM 
Pour comprendre mieux le projet et son objectif : 
Le produit fini est une interface streamlit dans laquelle l'utilisateur simule une demande de crédit. 
Voici la pipeline qui s'active suite à cela : 
- upload des pièces nécessaire à une demande de crédit (fiche de paie, ...)
- récolte des données contenues dans ces documents via OCR (tesseract ou modèle from scratch)
- extraction des features de ces textes grâce à un LLM 
- utilisation des features obtenues pour noter le crédit
À l'issue de cette pipeline l'utilisateur sait si oui ou non son dossier est suceptible de "passer". 
Peu importe le résultat il peut télécharger une fiche synthèse de son profil afin de mieux comprendre les forces et faiblesses de son dossier. 

## Structure du projet 

## Pour clôner le projet 
```bash 
git clone https://github.com/votrecompte/OCRedit.git 
cd OCRedit 
pip install -r requirements.txt 
