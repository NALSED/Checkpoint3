## Partie 1 : Gestion des utilisateurs


### Q.1.1.1 Créer l'utilisateur Lionel Lemarchand avec les même attribut de société que Kelly Rhameur.


![image](https://github.com/user-attachments/assets/fdb115b8-312c-43b2-9f19-60c566a8a950)

![image](https://github.com/user-attachments/assets/131f43fe-62b5-4bfd-a319-7ad70d5ec442)


### Q.1.1.2 Créer une OU DeactivatedUsers et déplace le compte désactivé de Kelly Rhameur dedans.
#### Clic droit sur son compte disable account
![image](https://github.com/user-attachments/assets/4d747c74-cd84-4a36-83d1-5f0b8bd85780)

![image](https://github.com/user-attachments/assets/54377111-eccc-4188-b528-16f8007e7fee)

![image](https://github.com/user-attachments/assets/3a5371c5-18d1-491b-89cd-8f5b7c9a0c39)

![image](https://github.com/user-attachments/assets/3111d70e-f1a3-4fdf-b12f-920f2e8d4a01)

![image](https://github.com/user-attachments/assets/89793510-85fe-46f4-898c-f7767bcd9e1e)

* #### Désactiver le compote de kely => clic droit Disable Account


### Q.1.1.3 Modifier le groupe de l'OU dans laquelle était Kelly Rhameur en conséquence.

* #### Remove le groupe => DirectionDesRessourcesHumaines

![image](https://github.com/user-attachments/assets/e8693dec-2d41-4de2-bed5-ef852657961a)


### Q.1.1.4 Créer le dossier Individuel du nouvel utilisateur et archive celui de Kelly Rhameur en le suffixant par -ARCHIVE.

![création de dossier  Lionel Lemarchand 1 1 4](https://github.com/user-attachments/assets/d76c5738-f134-48f8-b46a-ec56e6e3f506)

![archives 1 1 4](https://github.com/user-attachments/assets/79eacb42-8905-4992-9a6b-4519bb690406)


## Partie 2 : Restriction utilisateurs


### Q.1.2.1 Faire en sorte que l'utilisateur Gabriel Ghul ne puisse se connecter que du lundi au vendredi, de 7h à 17h.
![1 2 1 ghul 1](https://github.com/user-attachments/assets/26ee8856-280b-43a0-9e5a-4ddddf585e09)


![1 2 1 ghul 2](https://github.com/user-attachments/assets/7bba2c58-1d43-41bc-9101-459373c0e943)

![1 2 1 ghul 3](https://github.com/user-attachments/assets/9b3043ae-833a-4ec8-b649-3462b5002576)

![1 2 1 ghul 4](https://github.com/user-attachments/assets/ca4c9f4a-cc5c-4ad0-af38-ef25bae39294)

![1 2 1 ghul 5](https://github.com/user-attachments/assets/f1f4a05d-186e-4c92-8aab-85cfb3b847de)
### Q.1.2.2 De même, bloquer sa connexion au seul ordinateur CLIENT01.
### Dans account => Log On To => mettre le nom du PC demandé
![image](https://github.com/user-attachments/assets/61efad3f-0b39-4d9d-bd6a-8d2f43801652)



### Q.1.2.3 Mettre en place une stratégie de mot de passe pour durcir les comptes des utilisateurs de l'OU LabUsers.

![1 2 3 GPO 1](https://github.com/user-attachments/assets/dc0be852-4a68-4de5-af89-491e265cf818)

![1 2 3 GPO 2](https://github.com/user-attachments/assets/68d58b17-0251-4892-9234-889ebe9f7ea0)

![1 2 3 GPO 3](https://github.com/user-attachments/assets/dacab633-90c0-4752-a731-7fed1b4b62e8)

![1 2 3 GPO 4](https://github.com/user-attachments/assets/d83a6602-b734-49a9-abf7-1e04709a17f5)


![1 2 3 GPO 5](https://github.com/user-attachments/assets/f7fd897f-5753-4d51-b704-74386818039c)


![1 2 3 GPO 6](https://github.com/user-attachments/assets/d8608609-3aa3-4289-a23f-3a97805cb43e)


![1 2 3 GPO 7](https://github.com/user-attachments/assets/38166df2-d52b-4135-a923-946a6a62419e)

![1 2 3 GPO 8](https://github.com/user-attachments/assets/28774465-abec-4634-a3e6-632380eb0826)

![1 2 3 GPO 9](https://github.com/user-attachments/assets/c0db10b0-6e53-46aa-a3f8-f43dabe54be6)


## Partie 3 : Lecteurs réseaux

### Q.1.3.1 Créer une GPO Drive-Mount qui monte les lecteurs E: et F: sur les clients.

![1 3 1 mappage 1](https://github.com/user-attachments/assets/18e76706-2223-4b6d-b396-b8dfe340fc5b)

![1 3 1 mappage 2](https://github.com/user-attachments/assets/fd432588-4025-41a8-b3df-9612fa7e3eac)

![1 3 1 mappage 3](https://github.com/user-attachments/assets/635319b1-bb85-4c18-9a36-2af84eee92a1)


![1 3 1 mappage 4](https://github.com/user-attachments/assets/56289d73-924e-4bb2-bf29-57993203624a)

![1 3 1 mappage 5](https://github.com/user-attachments/assets/852007bd-0c36-4a45-959e-6f139743db63)

![image](https://github.com/user-attachments/assets/e6d3b0ff-45ec-4d7d-a86d-dda097ce3e21)

![image](https://github.com/user-attachments/assets/04328ad7-31da-4b4c-a67d-f5651412e84b)

![image](https://github.com/user-attachments/assets/43f9bc02-428f-4c05-8269-957e078d2ebb)


