
**Toute entité est transformée en table. Les propriétés de l'entité deviennent les attributs de la table. L'identifiant de l'entité devient la clé primaire de la table.**

<img width="726" alt="Capture d’écran 2024-08-14 à 17 59 47" src="https://github.com/user-attachments/assets/4c3e08ce-c1c2-42f0-8094-1470e0931933">

Afin de représenter la relation, on duplique la clé primaire de la table basée sur l'entité à cardinalité (1,n) dans la table basée sur l'entité à cardinalité (1,1). **Dans cet exemple nous somme dans une relation 1,N mais pour bien comprendre on notera les table x,N et x,1 car pour definir la relation il faut regarder le chiffre ou la lettre de droite**. Cet attribut est appelé clé étrangère. Les deux tables sont liées par une flèche nommée selon la relation, qui pointe de la table à clé étrangère vers la table qui contient la clé primaire correspondant

L'attribut No_Auteur qui est clé primaire de la table Auteur, devient clé étrangère dans la table Livre.


<img width="1137" alt="Capture d’écran 2024-08-14 à 18 02 26" src="https://github.com/user-attachments/assets/3e7158e5-6145-4523-a681-ac70daf0f177">


Nous devons distinguer plusieurs cas. Sachant qu'une relation binaire du type (1,1)-(1,1) ne doit pas exister il nous reste les 2 cas suivants:

 dans le cas d'une relation 1,1 On duplique la clé de la table basée sur l'entité à cardinalité (0,1) dans la table basée sur l'entité à cardinalité (1,1). 
:point_down: :point_down:


![Capture d’écran 2024-08-15 à 12 00 37](https://github.com/user-attachments/assets/0bd1892e-fc78-417f-9f45-3b3708acac29)


Dans le cas d'une Relation binaire (0,1)-(0,1), On duplique la clé d'une des tables dans l'autre. Lorsque la relation contient elle- même des propriétés, celles-ci deviennent également attributs de la table dans laquelle a été ajoutée la clé étrangère 

:point_down: :point_down:


![Capture d’écran 2024-08-15 à 12 06 32](https://github.com/user-attachments/assets/081657c2-dc13-43db-b89c-f91bda063869)




 Dans le cas d'une relation N,N On crée une table supplémentaire ayant comme clé primaire une clé composée des clés primaires des 2 tables. Lorsque la relation contient elle-même des propriétés, celles- ci deviennent attributs de la table supplémentaire. Une propriété de la relation qui est soulignée devra appartenir à la clé primaire composée de la table supplémentaire. 
 
:point_down: :point_down:

![Capture d’écran 2024-08-15 à 12 15 43](https://github.com/user-attachments/assets/26d626f9-b1fb-4947-9789-0916af7613a5)


Les relations ternaires:

Une relation ternaire est un type de relation qui implique trois entités distinctes. Cette relation est utilisée pour modéliser des situations où trois types d’entités participent simultanément à une association qui ne peut pas être décomposée efficacement en plusieurs relations binaires (c’est-à-dire entre deux entités seulement). 




![Capture d’écran 2024-08-15 à 15 08 24](https://github.com/user-attachments/assets/982614eb-f965-4348-9743-751b03b53488)


dans le shemat ci-dessous La relation habiter du type (x,n)-(x,1), est traduite par la migration de l'attribut Adresse dans la table Personne. La relation posséder du type (x,n)-(x,n) est traduite par la création d'une table supplémentaire du même nom. Cette table contient comme clé primaire composée, les clés des deux tables reliées Personne et Maison. On a donc simplement appliqué 2 fois de façon indépendante les règles de transfert MCD ? MLD.

:point_down: :point_down:


![Capture d’écran 2024-08-15 à 15 12 26](https://github.com/user-attachments/assets/79e3e6e6-07dd-448c-ab2a-03c105d11bcb)

**RECAPITULATIF**

![Capture d’écran 2024-08-15 à 15 16 34](https://github.com/user-attachments/assets/5cb1e103-58c4-4e28-b24c-4f058a4f0e95)

![Capture d’écran 2024-08-15 à 15 17 08](https://github.com/user-attachments/assets/e62a4b2b-5817-47f7-b72b-d2e6e5116359)

![Capture d’écran 2024-08-15 à 15 18 07](https://github.com/user-attachments/assets/8814ba9d-c81e-476a-b81e-58747e82f50a)

![Capture d’écran 2024-08-15 à 15 18 24](https://github.com/user-attachments/assets/a887f699-f16d-40fb-bdbb-4da61d27640a)

![Capture d’écran 2024-08-15 à 15 18 45](https://github.com/user-attachments/assets/2460f19f-ec04-4366-9774-9ae610cd334d)

**recap pour le ternaire**

![Capture d’écran 2024-08-15 à 15 19 54](https://github.com/user-attachments/assets/a6bac174-043f-4329-afaa-bf7c72f0d656)

![Capture d’écran 2024-08-15 à 15 20 07](https://github.com/user-attachments/assets/9fea6e55-852c-4cea-983c-8de9b8626cf9)




















