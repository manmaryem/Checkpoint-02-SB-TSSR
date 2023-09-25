# Checkpoint-02-SB-TSSR

## Exercice 2 : Réseaux et domaine

### 1. Résoudre le problème de ping entre Client1 et le serveur DC

le ping entre Client1 et le serveur DC focton bien.pour cela le deux machines sont connectées au même réseau , j'a verifié que le DHCP est activé ensuite j'ai désactivé le Firewall sur la machine DC 2019.

![image](https://github.com/manmaryem/Checkpoint-02-SB-TSSR/assets/137881827/1b9e775e-7033-4dd8-bd74-e7951c3c6234)

### 2. Résoudre la connection avec l'utilisateur jane.doe/Azerty123! sur Client1.

Pour pouvoir se connecter avec le comtpe de John Doe sur le Client1, j'ai créer le comptre de John Doe sur la machine clent 1

![image](https://github.com/manmaryem/Checkpoint-02-SB-TSSR/assets/137881827/317cd7ee-2d72-4301-b01c-f97c7180cc03)

ensuite je vais également dans le bureau a distance la machine Dc 2019 afin de créer 
![image](https://github.com/manmaryem/Checkpoint-02-SB-TSSR/assets/137881827/b9aae930-0aad-482e-b4c1-c5c98074e12c)

### 3. La Configuration du serveur DHCP*

Création de GPO pour interdir les accès aux utilisatuers, à partire du "Gestionnaire de serveur" sur la VM DC 2019, j'ai créer une GPO qui interdit l'accès au accès à l'invite de commande et au powershell
![image](https://github.com/manmaryem/Checkpoint-02-SB-TSSR/assets/137881827/bb700f9f-d023-4a6c-8b9e-7eef828b9480)

![image](https://github.com/manmaryem/Checkpoint-02-SB-TSSR/assets/137881827/0ed21c70-be39-4837-a4cf-715f8bc083bc)










