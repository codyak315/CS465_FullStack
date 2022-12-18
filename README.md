# CS465_FullStack
CS-465 Full Stack Development with MEAN

Architecture </br>
Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
Why did the backend use a NoSQL MongoDB database? <br></br>

Our frontend can be broken down into two main elements. Our first iteration of a web application involved sole usage of HTML, and later the use of templating via the use of Handlebars to create a website utilizing some basic JavaScript and Express. Our next iteration involved employing the use of Angular to produce an SPA that interfaced with Mongoose which acted as our NoSQL DB to extract the necessary data from our Mongo DB. This provided a means of responding to requests while also keeping the flow of data to a minimum by only updating the necessary elements of the application and not redundant information. 

Functionality </br>
How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components. <br></br>

JSON stands for JavaScript Object Notation. JavaScript itself is a programming language. To this end we use JavaScript to implement functionality and use JSON to hold data. For example in our application we held the data of our 'trips' as JSON, and utilized JavaScript functions to retrieve and augment that data, such as in our edit and add trip functionality that allows the changing of the data on the application. By setting up the application in this manner it allows for reusable components that save resources as we dont have to tear down and rebuild every element any time there is a change in the data. 

Testing </br>
Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application. <br></br>

In our full stack application there are various moving parts that all require thorough testing. To this end console logs were created to identify when methods such as GET or POST were successful (200) or unsuccessful (400). Third party programs helped prove these API endpoints such as the use of the Postman application. With the addition of security it became not only important to observe functionality, but that the functionality was only available to authenticated users. 

Reflection </br>
How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

I have appreciated the no-nonsense direct approach this course had on full stack development. In a lot of fields I feel that there can be a lot of convoluted information but in this course specifically you had clear directives, such as implementing add or edit functionality, security, or even simply booting up a homepage for our SPA. These clear actionable segments have taught me that if you know how to find the right questions, and you have patience then you can be a good developer. I know that I have much more to learn but I feel confident that I will be able to handle it moving forward in my professional career. 
