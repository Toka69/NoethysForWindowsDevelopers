Noethys
==================
Logiciel de gestion libre et gratuit de gestion multi-activités pour 
les accueils de loisirs, crèches, garderies périscolaires, cantines, 
TAP ou NAP, clubs sportifs et culturels...

Plus d'infos sur www.noethys.com

Certaines librairies présentes dans ce projet sont la propriété exclusive de Microsoft.

Installation des sources sur Windows et compilation
------------------

Installer les executables se trouvant dans le dossier binaries :
1) Python2.7 (penser à cocher la case "ajouter au path")
2) VCForPython27
3) Py2exe, wxPython et MYSQL-Python

Installer les modules python. Se placer à la racine du projet et saisir :
```
pip install -r requirements.txt
```

A ce stade, Noethys doit correctement fonctionner en executant :
```
noethys/Noethys.py
```

Pour compiler, se placer à la racine du projet et saisir:
```
python setup.py py2exe
```
