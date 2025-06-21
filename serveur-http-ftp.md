![Python](https://img.shields.io/badge/python-3.12-blue?logo=python&logoColor=yellow)


## Description
Ce programme permet de partager facilement des dossiers via un serveur HTTP ou FTP local grâce à une interface graphique simple.

### Fonctionnalités principales :

- #### Partage de dossiers par HTTP
    - Glissez-déposez un dossier dans le champ “Répertoire HTTP”
    - Cliquez sur “Lancer HTTP”.
    - Accés à ce dossier depuis un **navigateur web** grâce à l’URL indiquée.

- #### Partage de dossiers par FTP
    - Glissez-déposez un dossier dans le champ “Répertoire FTP”
    - Cliquez sur “Lancer FTP”.
    - Accés à ce dossier avec un client FTP (par ex. un **explorateur de fichiers**) à l’URL indiquée.

---

Code *python* disponible sur le [Github de nsi-mechain](https://github.com/nsi-mechain/outils/blob/main/serveur_http_ftp.py)

Nécessite l'installation de deux modules :

```bash
pip install pyftpdlib
pip install tkinterdnd2
```
