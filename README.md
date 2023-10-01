# SSH serveur

_______

Fourni un fichier de configuration valide pour un serveur OpenSSH permettant la configuration suivante :   

Le serveur écoute sur le port TCP 222 en IPv6 uniquement   
Seul l'utilisateur ayant le nom de login wilder peut se connecter   
La connexion par mot de passe est impossible. Une clé est nécessaire.   

____

## Installation d’un serveur SSH 

Installer serveur SSH avec _sudo apt install openssh-server -y_  

![image](https://github.com/techerbeatrice/ssh_server/assets/138071140/cfc0049a-e5bb-46e4-b344-70a4d25fd907)

___

Démarrer le service SSH et modifier le fichier de configuration du serveur SSH se trouvant dans le répertoire _“/etc/ssh/sshd_config_  

![image](https://github.com/techerbeatrice/ssh_server/assets/138071140/9f818def-41e8-4d6b-ab2c-a663bc0bc047)

![image](https://github.com/techerbeatrice/ssh_server/assets/138071140/f1376d49-f46d-479c-a6cb-95a78851f4aa)

![image](https://github.com/techerbeatrice/ssh_server/assets/138071140/f6e4f77a-c47d-43cf-bf07-eba16b132bd4)

![image](https://github.com/techerbeatrice/ssh_server/assets/138071140/cd8479f5-e500-4000-8db3-d5f1b3665ddf)

![image](https://github.com/techerbeatrice/ssh_server/assets/138071140/34af70ba-b24d-445d-825e-1c1c4505fbd3)
