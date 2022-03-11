# How-To-Structure-Your-Node-js-Project-To-Fit-Industry-Standard-Architecture



 -routes<br>
 -controllers<br>
 -services<br>
 -models<br>
 -config<br>
 -middleware<br>
 -utils<br>
 -helpers<br>
 -validations<br>
 -tests<br>
 --.env<br>
 --entry file(index.js or server.js or app.js)<br>

#Routes - Controllers - Services - Models Architecture

#HTTP Logic layer
<br> -(Routes + Controller)

#Bussiness Logic Layer
 <br>-(Services + Models/Data Access)


#Routes
 <br>-Endpoints<br>
 -Routing logic (Engaging Controller)<br>

#Controllers
 <br>-validation of request body<br>
 -Calling Services (Internal/External)<br>
 -Response handling<br>
 -Error handling<br>

#Services
<br> -Business Logic of the system<br>
 -Interfacing the DB<br>

#models/Data Access
<br> -Database modeling (Schema, query, and co)
