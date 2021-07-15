---
step: 2
description:  Mise à jour de la carte SD et du serveur web embarqué.
---

# **1. Première mise à jour**{: style="color:   #138ca2; opacity: 1;" }

Si vous venez de construire votre variomètre, il suffit de télécharger la dernière version du dossier "RootSD" correspondant à la version de votre firmware sur le [site de téléchargement](http://gnuvario-e.yj.fr/)
Après l'avoir décompressé, copiez les fichiers contenus dans ce dossier directement à la racine de votre carte SD.
Téléchargez ensuite le zip "fichiers web" correspondant à votre version (fichier www.gz) et après l'avoir décompressé, copiez le également à la racine de votre carte SD.
N'oubliez pas de télécharger les fichiers topographiques de votre région [ici](https://vps.skybean.eu/agl/) et de les copier dans le dossier AGL.

Au démarrage de votre vario, le serveur web se mettra à jour puis le vario redémarrera. Votre vario est prêt à être [configuré]({{site.baseurl}}/manuel/page_web.html).     

# **2. Mises à jour suivantes**{: style="color:   #138ca2; opacity: 1;" }

Les mises à jour suivantes sont similaires mais certains fichiers ne sont pas à remplacer pour ne pas perdre vos données et paramètres.
 
Téléchargez la dernière version du dossier "RootSD" correspondant à la version de votre firmware sur le [site de téléchargement](http://gnuvario-e.yj.fr/)
Après l'avoir décompressé, copiez les fichiers contenus dans ce dossier directement à la racine de votre carte SD **SAUF**{: style="color:   #ff3349; opacity: 1;" }:

**Les fichiers:**{: style="color:   #138ca2; opacity: 1;" }

-`prefs.jso` (Préfèrences du webserveur)

-`params.jso` (Paramètres du web serveur)

-`variocal.cfg` (votre calibration)

`-variosound.cfg`(votre courbe de son personnalisée)

`-wifi.cfg` (vos codes wifi)

**Les dossiers:**{: style="color:   #138ca2; opacity: 1;" }

`-AGL` (vos fichiers topographiques déja téléchargés)

`db` (la base de données incluant les vols classés et sites enregistrés)

`vols` (si vous avez des vols non encore classés).

Téléchargez ensuite le zip "fichiers web" correspondant à votre version (fichier www.gz) et après l'avoir décompressé, copiez le également à la racine de votre carte SD.

Au démarrage de votre vario, le serveur web se mettra à jour puis le vario redémarrera. 

Avant tout mise à jour, nous vous conseillons de faire une copie de sauvegarde de votre carte SD.


