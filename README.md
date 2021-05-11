# Client-server_PearlBegue-khousheetaJebodh
# Projet-SE 
## _Client Serveur_

Le projet est de créer un communication entre un client et un serveur d'ou on peut faire plusieur demande de commande et le serveur l'execute.


## Fonctionnalité

- Le client fait sa demande au serveur comme un fichier, une liste des fichiers, effacer.
- Le serveur attend le client et répond aux demandes du client.
- Le serveur peut recevoir des demandes specific d'une repetoire indiquez

## Compiler
- Entrez dans - cd bin
- Ecrivez - cmake ..
- Puis ecrivez - make


## Execution
Pour lancer la programmation du projet on doit:
Premièrement on doit lancer le program serveur 
```sh
./serveur
```

Puis on lance le program client pour pouvoir faire notre demande.

```sh
./client 127.0.0.1
```
Note: si l'utilisateur mette pas d'IP address automatiquement il prend l'IP host local.
Ex. Comme ceci
```sh
./client 
```

## Utiliser
### Client
Comment le program fonction et comment faire votre demande.
Étape 1: Demande quelle commande allez-vous exécuter.

```sh
SELECT A MODE
1)Find a Specific Files in a The Server Directory
2)List all Files from The Server Directory
3)Remove a File from The Server Directory
4)Exit the connection
```

Étape 2: Vous indiquez quelle commande vous chosiez

```sh
Select 1/2/3/4
2
```

Étape  3: Inserez le répertoire du fichier que vous voulez modifier/utiliser

```sh
Enter the path to the file : ../resources
```


Vu que la commande 2 est lister les fichiers dans le dossier ressources voici le résultat.

```sh
.
..
test2.txt
```
### Serveur
Pendant qu'on lancez le serveur le message afficher sera:
```sh
Listen
```
## Github
Propriétaire : Jebodh Khousheeta
Collaborateur : Begue Pearl
