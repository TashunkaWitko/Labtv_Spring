# Labtv_Spring

IT

Progetto LabForTraning che emula le funzionalità delle chiamate API (labtv) e un CRUD di base utilizzando Thymeleaf (labtv_monolitico).

Il database labtv.sql non è stato creato da me, mi è stato assegnato ed il mio compito è stato quello di costruirvi attorno in modo da ottenere i JSON dei dati presenti nel database.

lab_tv.zip emula alcune chiamate API di base che possono essere visualizzate utilizzando servizi come Postman, utilizza la struttura di base di Entità, Controller e Servizi.

localhost:8080/api-labtv/api/evidenze ===> Per ottenere dalla tabella delle prove tutti i dati contenuti nel database in formato JSON

localhost:8080/api-labtv/api/films ===> Per ottenere tutti i dati contenuti nel database in formato JSON dalla tabella film

localhost:8080/api-labtv/api/films/3 ===> Per ottenere tutti i dati contenuti nel database in formato JSON dalla tabella film corrispondente all'id indicato nell'URL (sono consapevole di non aver incluso messaggi di errore nel caso venga dato un valore errato (è un'applicazione che necessita ancora di un po' di lavoro).

localhost:8080/api-labtv/api/trailers/3 ===> Per ottenere tutti i dati contenuti nel database in formato JSON dalla tabella trailers dato l'id del film corrispondente

localhost:8080/api-labtv/api/films/titoli/{title} ===> Per ottenere tutti i dati contenuti nel database in formato JSON dalla tabella film dato il titolo del film (la variabile {title} è la parametro da passare, anche se il titolo non è esattamente lo stesso darà le risposte corrette, per raggiungere questo obiettivo ho implementato una query personalizzata utilizzando l'operatore LIKE nella query associata al titolo)
LabForTraning project emulating the functionalities of API calls (labtv) and a basic CRUD using thymeleaf (labtv_monolitico).

EN

LabForTraning project that emulates the functionality of API calls (labtv) and a basic CRUD using Thymeleaf (labtv_monolitico).

The database labtv.sql was not designed by me but was given and my task was to build around it in order to obtain JSONs of the data present in the database.

lab_tv.zip emulates some basic API calls that can be visualized using services like Postman, it uses the basic structure of Entities,Controllers and Services.

localhost:8080/api-labtv/api/evidenze  ===> to obtain all data contained in the database in JSON format from the evidenze table

localhost:8080/api-labtv/api/films ===> to obtain all data contained in the database in JSON format from the films table

localhost:8080/api-labtv/api/films/3 ===> to obtain all data contained in the database in JSON format from the films table corresponding to the id given in the URL 
(I am aware i did not include error messages in case an erroneous value is given. It's an application that still needs some work).

localhost:8080/api-labtv/api/trailers/3 ===> to obtain all data contained in the database in JSON format from the trailers table given the id of the corresponding film

localhost:8080/api-labtv/api/films/titoli/{title} ===> to obtain all data contained in the database in JSON format from the films table given the title of the movie
(the {title} variable is the parameter to pass, even if the title is not exactly the same it will give the correct respons, in order to achieve this i implemented a custom query using the 
LIKE operator in the query associated with title)
