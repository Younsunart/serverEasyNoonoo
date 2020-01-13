# serverEasyNoonoo

Create a new repository on your machine.

Enter the next command on your terminal : 
# git clone https://github.com/Younsunart/serverEasyNoonoo.git

go to the back repository on your terminal and type : 
# npm i express body-parser mongoose cors

launch the server by enter the next command in your terminal :
# node server.js

Open your postman, and configure it as below :

link for the request : http://localhost:4000/api/calculscharges
type of the request : POST
content-type : application/json

see the next photos to be sure how to configure it

![alt text](https://i.postimg.cc/KzJPxHmB/Screenshot-2020-01-13-at-10-03-19.png)

Enter the request as below : 

![alt text](https://i.postimg.cc/25ddX5JH/Screenshot-2020-01-13-at-10-02-08.png)

The request must match the request below, just change values : 

{
	"dateDebutAnnee" : 2020,
	"enfantPlusJeune" : 4,
	"nbEnfants" : 1,
	"parentIsole" : true,
	"ressourcesAnnuelles" : 25000,
	"heuresSup" : 8,
	"heuresHebdo" : 40,
	"tauxHoraire": 10.40,
	"repartitionFamille" : 0.5,
	"alsaceMoselle" : false,
	"trancheA" : true, 
	"tauxParticipationCotisations" : 0.5
}
