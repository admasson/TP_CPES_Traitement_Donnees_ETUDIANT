# TP_CPES_Traitement_Donnees_ETUDIANT
Version étudiant du TP de traitement de données CPES2

Le notebook est accessible sur le dépôt Github suivant: https://github.com/admasson/TP_CPES_Traitement_Donnees_ETUDIANT. 

Il peut être téléchargé en cliquant sur "code" puis "Download ZIP", ou bien avec une commande github en ouvrant un terminal dans le dossier de votre choix et en tapant:

$ git clone https://github.com/admasson/TP_CPES_Traitement_Donnees_ETUDIANT.git

Commencer par récuperer le TP et placez les fichiers dans *Documents* puis ouvrir un terminal et taper la commande suivante :

```
$ cd Documents/NOM_DU_DOSSIER/
```

Pour que le notebook fonctionne correctement, celui-ci doit être lancé via **Jupyter Lab** (et pas Jupyter Notebook !) et requiert l'installation de quelques extensions pour l'utilisation de widgets matplotlib. Pour cela, lancer depuis le terminal les commandes suivantes :

```
$ pip install -r requirements.txt
$ jupyter labextension install @jupyter-widgets/jupyterlab-manager jupyter-matplotlib
```

Lancer ensuite le notebook avec :

$ jupyter lab

ou

$ jupyter lab TP_Traintement_Donnees.ipynb
