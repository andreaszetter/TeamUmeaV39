# TeamUmeaV39
Grupprojekt för Chas academy Team Umeå

Flödes schema, login knapp:
Börja med att trycka på logga in knappen som skickar en HTTP begäran till servern. Servern söker i databasen efter användaren och användarens info.

OM status kod OK: Databasen returnerar informationen (inloggningsinfo) till servern och presenteras för användaren. Användarens informatin presenteras. 

Om statuskod EJ OK: Om användaren har angett fel användarnamn eller lösenord skickas felkod till användaren. Servern returnerar informationen till frontend och sidan. Informationen presenteras för användaren att försöka logga in igen eller skapa en användare.
