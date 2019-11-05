# PHP-REST-API-OPGAVEN

for at kunne hente alt data på alle brugere (data som er json formateret), skal du connecte til entrypoint url http://localhost:8888/pdo-opgaven/pdo-opgave-master/index.php med GET method. DEFAULT.

hvis du vil have info på en bestemt bruger skal du bruge GET method igen men med ID'et på den bruger du vil have info på. 
hvis det ID ikke findes, eller der sker en anden fejl, bliver der vist en fejl meddelelse ellers bliver den returneret med en OK og vist som json formateret data.

for at redigere/put/post/update skal du connecte til entrypoint url med PUT eller POST method på ID'et på den bruger du vil redigere info på. 
hvis det ikke virker bliver der vist en fejl meddelelse ellers bliver den returneret med en OK.

for at slette/delete skal du connecte til entrypoint url med DELETE method på ID'et på den bruger du vil slette.
hvis det ikke virker bliver der vist en fejl meddelelse ellers bliver den returneret med en OK.

for at oprette en ny bruger, skal du connecte til entrypoint url med POST method. 
hvis det ikke virker bliver der vist en fejl meddelelse ellers bliver den returneret med en OK.
