
**Toute entité est transformée en table. Les propriétés de l'entité deviennent les attributs de la table. L'identifiant de l'entité devient la clé primaire de la table.**

<img width="726" alt="Capture d’écran 2024-08-14 à 17 59 47" src="https://github.com/user-attachments/assets/4c3e08ce-c1c2-42f0-8094-1470e0931933">

Afin de représenter la relation, on duplique la clé primaire de la table basée sur l'entité à cardinalité (1,n) dans la table basée sur l'entité à cardinalité (1,1). **Dans cet exemple nous somme dans une relation 1,N mais pour bien comprendre on notera les table x,N et x,1 car pour definir la relation il faut regarder le chiffre ou la lettre de droite**. Cet attribut est appelé clé étrangère. Les deux tables sont liées par une flèche nommée selon la relation, qui pointe de la table à clé étrangère vers la table qui contient la clé primaire correspondant

L'attribut No_Auteur qui est clé primaire de la table Auteur, devient clé étrangère dans la table Livre.


<img width="1137" alt="Capture d’écran 2024-08-14 à 18 02 26" src="https://github.com/user-attachments/assets/3e7158e5-6145-4523-a681-ac70daf0f177">
<br>





dans le cas d'une relation 1,1 On duplique la clé de la table basée sur l'entité à cardinalité (0,1) dans la table basée sur l'entité à cardinalité (1,1).



