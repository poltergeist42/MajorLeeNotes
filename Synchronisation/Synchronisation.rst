+++++++++++++++++++++++++++++++++++++
La synchronisation / sauvegarde*
+++++++++++++++++++++++++++++++++++++

:Auteur: J.Soranzo
:Date: Octobre 2019
:Societe: VoRoBoTics
:Entity: VoLAB

.. contents:: Table des matières Allway Sync


================================
AllwaysSync
================================

`Site du fournisseur`_

.. _`Site du fournisseur` : https://allwaysync.com

**AllwaysSync sait synchronisé sur OneDrive**


Synchronisation automatique
================================

`Voir cette page`_

.. _`Voir cette page` : https://allwaysync.com/support/manuals/service


limitations
================================
allways sync en version limité est limité à 40k fichiers/mois glissants.

::

	the limitations may not allow Customer to process more than 40,000 files in any consecutive 30-days.

version pro 26$


================================
SyncThing
================================
`Site officiel de Synthind`_

.. _`Site officiel de Synthind` : https://syncthing.net/

Assez déroutant dans ses concepts.

`Vidéo Youtube de Paf Le Geek`_

.. _`Vidéo Youtube de Paf Le Geek` : https://www.youtube.com/watch?v=zXhkFNtg6hw

Très sécuritaire mais nécessite une installation sur chaque machine du réseau de synchronisation.

Je ne pousse pas les test plus loin.

======================================
Altrenatives
======================================
Questions : logiciels de sauvegarde ou logiciel de synchronisation ?

::
	Allway Sync uses innovative synchronization algorithms to synchronize your data

Autres logiciels possibles : 

La liste peut-ête longue comme par exemple sur `capterra.com`_

.. _`capterra.com` : https://www.capterra.com/file-sync-software/

ou encore mieux la liste de `Wikipedia`_

.. _`Wikipedia` : https://en.wikipedia.org/wiki/Comparison_of_file_synchronization_software

Freefile sync ne synchronise pas dans le cloud mis à part Google drive et FTP SFTP

Pas d'accès ftp sur OneDrive

BitTorrent Sync à revoir pas opensource


================================
Logiciels de sauvegarde 
================================
Il y en a plétor visiblement, des payant et des gratuits

Sur `Techadvisor.fr`_

- Acronis True Image 
- Bvckup 2 
- EaseUS Todo Backup Free 
- O&O AutoBackup 6 
- Paragon Backup & Recovery Home 
- Backblaze 
- Ashampoo Backup Pro 14 
- IDrive 

Pour la pluspart payants.

Cobian backup

Pas Seafile (nécessite un serrver et plus synchro)

`Baccula`_ bien compliqué : Bacula is a set of computer programs that permits the system 
administrator to manage backup, recovery, and verification of computer data across a network 
of computers of different kinds.


visiblement baucoup de solutions nécessite un serveur 

`Iperius backup`_ - pas poursuivi car payant.

.. _`Iperius backup` : https://www.iperiusbackup.fr/backup-software-windows.aspx



Sur `Korben 5 gratuits`_ :

- Saft Backup : plus été mis à jour depuis 2011
- BackupChain : version gratuit + payant 50€ environ
- EaseUS Todo Backup : verion gratuite limitée
- AceBackup : plus mis à jour depuis 2012
- Autover :  Il tourne en arrière-plan, met à jour dès qu’une modification a été apportée dans les dossiers à surveiller

Plus un bonnus dans le commentaire : Veeam Endpoint Backup Free Edition (pas trouvé de lien)

Préconisations Pierre
====================================================================================================
Borg 

Open source
====================================================================================================
`Duplicati 2.0`_ à l'air bien et un download Synology sur leur site !!! Ne supporte pas les FTP en
tant que source. testé. S'utilise au travers d'une interface WEB !


`Cobian`_ dev arrêté en avec la version 11 en 2013

`Amanda`_ AMANDA (Advanced Maryland Automatic Network Disk Archiver) est un logiciel libre de 
sauvegardes informatiques. Il est utilisé pour sauvegarder via le réseau un ensemble de postes 
clients et de serveurs (Unix, Linux, et Windows via Samba ou Cygwin).
Il a été initialement développé à l'université américaine du Maryland, sous licence BSD.
Au même titre que Bacula, Amanda est considérée comme étant une alternative viable aux 
outils de sauvegarde propriétaire (source Wikipédia.fr). Oui mais.. ça m'a l'air d'être tout en 
ligne de commandes et pour du Linux ! Redirigé vers ZManda mais on tourne en rond. Très mauvaise 
expérience de navigation.




.. _`Baccula` :  https://www.bacula.org/

.. _`Techadvisor.fr` : https://www.techadvisor.fr/banc-essai/logiciels/logiciel-sauvegarde-windows-3783174/

.. _`Korben 5 gratuits` : https://korben.info/5-logiciels-gratuits-pour-sauvegarder-votre-windows.html

.. _`Duplicati 2.0` :  https://duplicati.com

.. _`Cobian` :  https://www.cobiansoft.com/ 

.. _`Amanda` :  http://www.amanda.org/download.php

FreefileSync
====================================================================================================


================================
Weblinks
================================

.. target-notes::