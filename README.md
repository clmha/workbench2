# Établi de mécanicien
Ce projet est un établi de mécanicien (code de projet WB2) pour la maison construit à partir de matériaux aux dimensions courantes en Amérique du Nord.

La technique la plus complexe utilisée dans ce projet est le joint à mi-bois.

![Résultat final vu de face](image/workbench2.jpg)

# Matériaux
Si vous ne faites aucune erreur de coupe, vous aurez besoin de :

* (4) Madrier 2x4x8' ;
* (2) Panneau de contreplaqué 3/4"x2'x4' ;
* (1) Panneau dur 1/8"x2'x4'.

 L'exemple en photo a été réalisé en épinette.

# Quincaillerie

* Colle de construction ;
* Clous 1 1/2" ;
* Clous de finition 1/2" ;
* Clous de finition 1 1/4" ;
* Vis à bois #8 1 1/4" ;
* Vis pour trou en angle #8 1" ;
* Vis pour trou en angle #8 2 1/2".

# Outils
Hormis les outils de base (p. ex. ruban à mesurer), vous aurez également besoin de :

* Banc de scie pour découper les moulures ;
* Gabarit pour faire les trous en angle ;
* Perceuse/visseuse ;
* Scie à onglet pour découper précisement les madriers ;
* Scie circulaire pour découper les panneaux.

# Liste des documents
* WB2-ASY-001.pdf : dessin d'ensemble du projet avec la liste des pièces.

# Environnement de développement
* Windows 10 comme système d'exploitation ;
* QCAD Professional pour les dessins techniques ;
* LibreOffice 6.* pour les documents ;
* PDFtk pour manipuler les fichiers PDF ;
* Visual Studio Build Tools 2019 pour les outils de développement de base.

# Construire les artefacts
Avec l'environnement de développement correct, il vous suffit de lancer la commande "nmake" depuis une invite de commande de développeur pour Visual Studio 2019 ("Developer Command Prompt for VS 2019") à la racine du projet. Les documents seront générés dans le répertoire "build".

En cas d'erreurs "'X' n'est pas reconnu en tant que commande interne ou externe [...]", vérifiez que les exécutables de LibreOffice, QCAD, PDFtk sont dans votre PATH.
