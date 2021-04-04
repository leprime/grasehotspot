Vous avez des probèmes d'Upload sur votre serveur Ubuntu sur lequel vous avez
installé GraseHotspot? Ne vous inquietez pas.

Copiez ce script dans le dossier
 /etc/init.d/
Puis rendez le executable par
 sudo chmod +x /etc/init.d/solvenetwork.sh
Ensuite ajouter le script dans le groupe des scripts d'initialisation de type système avec la commande 
sudo update-rc.d solvenetwork.sh defaults

Puis redemarrer votre serveur et le tour est joué
