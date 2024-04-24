# Installation-manuellement-MySQL
Installation manuel MySQL linux 
Salut cher visiteur : 
Ceci est un procédure d'installation manuellement MySQL. 
        #1er Méthode : 
Vous devez télécharger le fichier code source MySQL vers le site officiel 
voici le lien : https://dev.mysql.com/downloads/mysql/
Télécharger selon votre préférence le version du fichier.
Pour moi j'ai téléchargé le version 8.0.3
Apres le téléchargement : vous avez un fichier comme ceci : mysql-8.0.3.tar.gz 
Et vous devez le décompresser et désarchiver on utilisant le commande gunzip et tar 
1) gunzip mysql-8.0.3.tar.gz
2) tar mysql-8.0.3.tar
C'est terminée vous avez réussi à le décompresser et desarchiver.
Il existe un methode qui decompresser le fichier le desarchiver en meme temps on utilisant le commande tar voici le syntaxe : tar -xfv mysql-8.0.3.tar.gz
Maintenant vous avez un dossier se nomme : mysql-8.0.3
Maintenant vous devez installer cmake et openSll si deja installer vous pouvez sauter cet étape : Aller sur le site officiel www.openssl.org/source/openssl-1.1.1.tar.gz 1)télécharger le fichier après 2)décompresser et desarchiver ! 3)cd openssl.1.1.1 4) ./configure 5)make 6)sudo make install  et pour le cmake : aller sur cet lien : https://github.com/bitware/cmake/releases/donwloads/v3.22.0/cmake-3.22.0.tar.gz 1)tar -xfv cmake-3.22.0.tar.gz 2)cd cmake-3.22.0
3) ./bootstrap 4)make 5)sudo make install
Opensll et cmake sont des dépendances de cet installation
Vous devez execute ces commandes maintenant :
$cd mysql-8.0.3
$ : ./configure
$ : make
$ : sudo make install 
