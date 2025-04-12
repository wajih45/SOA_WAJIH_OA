![Capture d'écran 2025-04-12 235145](https://github.com/user-attachments/assets/b1b148b2-2a04-442f-afe8-6031abb67a01)
![Capture d'écran 2025-04-12 235123](https://github.com/user-attachments/assets/11f0fbe0-2c27-4f33-a939-a5dae516fa11)
[Postman.txt](https://github.com/user-attachments/files/19722270/Postman.txt)
![Capture d'écran 2025-04-12 235232](https://github.com/user-attachments/assets/1866ab66-ffc6-42ec-bd98-264b84751419)
![Capture d'écran 2025-04-12 235216](https://github.com/user-attachments/assets/02be40cc-471b-4e45-b0fe-cfba0b945c9a)













           base H2 : http://localhost:8087/h2-console.
		   http://localhost:8087/
		   
		   JDBC URL : jdbc:h2:mem:restdb
		   port : 8087

           Username : sa

           Password : (vide)





Postman :        
Liste des étudiants
          http://localhost:8087/api/students
                           GET
						   Headers :
                           Accept: application/json
						   
						   

 POST /api/students (Créer un étudiant)
Méthode : POST

URL : http://localhost:8087/api/students

Headers :
Content-Type: application/json

Body (raw JSON) :

json
Copy
{ "nom": "Durand", "prenom": "Sophie" }
