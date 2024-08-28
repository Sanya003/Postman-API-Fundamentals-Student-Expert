# Postman-API-Fundamentals-Student-Expert
This repository contains detailed solutions to the tasks from the Postman API Fundamentals Student Expert Program. The program is designed for students and professionals looking to enhance their API skills, providing hands-on experience calling an API. This repository serves as a valuable resource for deepening your API knowledge and skills. 

<img src="https://everpath-course-content.s3-accelerate.amazonaws.com/instructor%2F26fp2261340y1ukokimvca8su%2Fpublic%2F1654279171%2FScreen+Shot+2022-06-03+at+1.58.53+PM.1654279171498.png" width="500"/>

### TASK 1 - Make the request
Make a _request_ named "skill check".

### TASK 2 - Add a query parameter called "movieName"
The request should have a _'movieName'_ parameter with a value set to any movie.

### TASK 3 - Turn your base URL into a variable
Simplify the request by replacing the URL with a _collection variable_ named '**skillcheckBaseUrl**'.

### TASK 4 - Use API Key authorization
The movie theater API requires the requests to be _authorized_. Add an _API key_ of "student-expert" and a _value_ of "skillcheck" at the **request level** using Authorization tab.
>_Make sure to add authorization at the request level, not at the collection level_

### TASK 5 - Add a JSON body with the property "actorName"
The skillcheck request should be a JSON body with a property called _"actorName"_ and a value set to any actor from the movie.
_Send your request to get a response from the API_.

### TASK 6 - Set a variable using a post-response script
Set the _actorName_ as a **collection variable** named "favoriteActor". In the Post response scripts tab of the request, write a _script_ to get the actorName from the response body and save the value as a new collection variable called "favoriteActor".
>_Send a request again and confirm this works by checking the collection variable page to see if the value is updated._



