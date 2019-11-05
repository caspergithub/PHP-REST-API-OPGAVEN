# PHP-REST-API-OPGAVEN

Rest api til user management

entrypoint: URL: http://localhost/user-rest-api/API/entrypoint.php

API functions
-------------

Get all users:
method: GET

returns json data with: id, username, email, password.

__________________________________________________________________________________


Get single user: 
method: GET

parameters: "id" value integer (user id from data)

returns json data with: id, username, email, password.

__________________________________________________________________________________


Make new user:
method: POST

body: json formattet: username, email, password. 

__________________________________________________________________________________


Update user:
method: PUT

body: json formattet: username, email, password. Send values to update.

eks: 
{"email":"insert your new data here"}
{"email":"insert your new data here","username":"insert your new data here"}

__________________________________________________________________________________


Delete single user:
method: DELETE

parameters: "id" value integer (user id from data) 
returns json data with: errorcode.



==============================================================================================================================


For at kunne hente alt data på alle brugere (.json formateret data), skal du connecte til entrypoint url http://localhost:8888/pdo-opgaven/pdo-opgave-master/index.php med en GET method. DEFAULT.

hvis du vil have info på en bestemt bruger skal du bruge en GET method igen men med ID'et på den bruger du vil have info på. 
hvis det ID ikke findes, eller der sker en anden fejl, bliver der vist en fejl meddelelse ellers bliver den returneret med en OK og vist som json formateret data.

for at redigere info på en bruger skal du connecte til entrypoint url med en PUT method på ID'et på den bruger du vil redigere info på. 
hvis det ikke virker bliver der vist en fejl meddelelse ellers bliver den returneret med en OK.

for at slette en bruger skal du connecte til entrypoint url med en DELETE method på ID'et på den bruger du vil slette.
hvis det ikke virker bliver der vist en fejl meddelelse ellers bliver den returneret med en OK.

for at oprette en ny bruger, skal du connecte til entrypoint url med en POST method. 
derefter skal du indtaste det data der skal oprettes og vælge accept. 
hvis det ikke virker bliver der vist en fejl meddelelse ellers bliver den returneret med en OK.
