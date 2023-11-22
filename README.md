# Labtv_Spring
LabForTraning project emulating the functionalities of Api calls and a basic CRUD using thymeleaf.

The database labtv.sql qas not designed by me but was given and my task was to build around it in order to obtain JSONs of the data present in the database.

lab_tv.zip emulates some basic API calls that can be visualized using services like Postman, it uses the basic structure of Entities,Controllers and Services.


localhost:8080/api-labtv/api/evidenze  ===> to obtain all data contained in the database in JSON format from the evidenze table

localhost:8080/api-labtv/api/films ===> to obtain all data contained in the database in JSON format from the films table

localhost:8080/api-labtv/api/films/3 ===> to obtain all data contained in the database in JSON format from the films table corresponding to the id given in the URL 
(I am aware i did not include error messages in case an erroneous value is given. It's an application that still needs some work).

localhost:8080/api-labtv/api/trailers/3 ===> to obtain all data contained in the database in JSON format from the trailers table given the id of the corresponding film

localhost:8080/api-labtv/api/films/titoli/{title} ===> to obtain all data contained in the database in JSON format from the films table given the title of the movie
(the {title} variable is the parameter to pass, even if the title is not exactly the same it will give the correct respons, in order to achieve this i implemented a custom query using the 
LIKE operator in the query associated with title)
