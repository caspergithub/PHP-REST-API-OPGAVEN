# PHP-REST-API-OPGAVEN

For at kunne hente alt data på alle brugere (.json formateret data), skal du connecte til entrypoint url http://localhost:8888/pdo-opgaven/pdo-opgave-master/index.php med GET method. DEFAULT.

hvis du vil have info på en bestemt bruger skal du bruge GET method igen men med ID'et på den bruger du vil have info på. 
hvis det ID ikke findes, eller der sker en anden fejl, bliver der vist en fejl meddelelse ellers bliver den returneret med en OK og vist som json formateret data.

for at redigere info på en bruger skal du connecte til entrypoint url med PUT, POST eller PATCH method på ID'et på den bruger du vil redigere info på. 
hvis det ikke virker bliver der vist en fejl meddelelse ellers bliver den returneret med en OK.

for at slette en bruger skal du connecte til entrypoint url med DELETE method på ID'et på den bruger du vil slette.
hvis det ikke virker bliver der vist en fejl meddelelse ellers bliver den returneret med en OK.

for at oprette en ny bruger, skal du connecte til entrypoint url med POST method. 
derefter skal du indtaste det data der skal oprettes og vælge accept. 
hvis det ikke virker bliver der vist en fejl meddelelse ellers bliver den returneret med en OK.
