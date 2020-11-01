# Admin

Detta är ett repo för mitt admingränssnitt. Här finner man filerna som har med sidans inloggning och och administration att göra.

Sidorna är skapade i PHP och fungerar som följer:

Login.php – härfirån kan man logga in till administrationssidan. 

Admin.php – Här kan man läsa ut, skriva nya, radera och uppdatera poster som inloggad administratör. Datan hämtas och postas med hjälp av ett API. 

Logout.php – förstör sessions-variabeln och loggar ut användaren och tar användaren tillbaka till login-sidan. 

För att komma åt login och admin skrivs följande in i adressfältet:

https://yofal.se/miun/webb3projekt/src/login.php
