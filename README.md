# restService
Rest Service test with Spring Boot

• Created a simple REST service using Spring Boot.

• Includes three classes of Main test application, Greeting class, and controller for the
Greeting class.

• Greeting Class is an object with two values: id and content.

• Greeting controller includes a template that adds the word “Hello, ” to the first of the
content.

• In the controller default value for the content has been given as “User” so the default
message will be “Hello, User!”

• If the content is provided by the user then the output will be “Hello, //Content// !”

• This controller creates a subpage of /Greeting in our service that will generate the
message mentioned above.

• The class RestServiceTestApplication simply runs our service and the service is
reachable by http://localhost:8080/Greeting for the default greeting and
http://localhost:8080/Greeting?name=Amir for assigning the content text.

• A jar package has been created for easy use of the service in case of usage in a server.


<img width="1680" alt="Screen Shot 2022-04-14 at 7 54 02 PM" src="https://user-images.githubusercontent.com/70853495/163450488-41a51548-3b19-47c3-9bba-8c2867033388.png">
• Service running with default name “User”



<img width="1680" alt="Screen Shot 2022-04-14 at 7 54 18 PM" src="https://user-images.githubusercontent.com/70853495/163450550-fa1f5257-870a-4406-b612-b35d9e2cbd1e.png">
• Service running with default name “User”
