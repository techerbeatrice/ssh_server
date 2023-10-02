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

Démarrer le service SSH  

![image](https://github.com/techerbeatrice/ssh_server/assets/138071140/c177a103-2599-4bc1-b5b6-a7654fef8138)

![image](https://github.com/techerbeatrice/ssh_server/assets/138071140/f1376d49-f46d-479c-a6cb-95a78851f4aa)

![image](https://github.com/techerbeatrice/ssh_server/assets/138071140/f6e4f77a-c47d-43cf-bf07-eba16b132bd4)

____

Le serveur écoute sur le port TCP 222 en IPv6 uniquement  
Seul l'utilisateur ayant le nom de login wilder peut se connecter  
La connexion par mot de passe est impossible. Une clé est nécessaire. 

paire de clés SSH a été générée    

![image](https://github.com/techerbeatrice/ssh_server/assets/138071140/08358a6b-6152-4e62-b434-27ebabddd941)

et modifier le fichier de configuration du serveur SSH se trouvant dans le répertoire _“/etc/ssh/sshd_config_ 

![image](https://github.com/techerbeatrice/ssh_server/assets/138071140/3e21973c-f6a0-4a4b-9cbc-e94ad007b61a)

![image](https://github.com/techerbeatrice/ssh_server/assets/138071140/b26372b7-e18d-479c-99e1-46838d0d845a)

![image](https://github.com/techerbeatrice/ssh_server/assets/138071140/1d52b5a8-bbc3-4e2a-b684-5ded122a8150)


  




