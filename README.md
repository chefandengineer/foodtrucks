A Minimum Version of SF Food Trucks 
===================================
This is a minimum working version of SF Food Trucks. A web site for people to find near 
by food trucks given zipcode or address. Results will be retrieved and show results in a
list view as well as on the map. 

Due to personal time constraints, the current working version covers the most basic function. 
However, the project structure is architured to easily scale in terms of development and test. 


Tao Jiang 

GitHub : https://github.com/chefandengineer

LinkedIn : https://www.linkedin.com/profile/view?id=104740077
		

Project Selected : Food Trucks 

Heroku Link : http://peaceful-island-7525.herokuapp.com/

Technical Track : Full Stack


Technical Stack Choices 
-----------------------
1. Front End : Bootstrap, Backbone.js, Underscore.js, Require.js (minimum experience)
2. Back End : Node.js, Restify.js, Require.js (no experience)
3. Database : Mongoose.js, MongoDB (no experience)
4. Test Frmework : Mocha.js, Require.js (no experience)


Development Descisions 
----------------------
Front End : 

1. Considering this will be a simple applcation, bootstrap is the best choice to rapidly build clean UI
2. Backbone.js essetially provides the client side MVC. It helps structure and modular the code, decouples views and data interaction(RESTful API) in the front end. It gives the application the power to scale comparing to a project of endless jQuery callbacks. It's light and open source therefore easy to learn and to find support. Comparing to other similar alternative, Ext js is robust but it's commercial. Angular.js is also powerful but a little heavy for building this small project.
3. Underscore gives the ability to reuse all the front end HTML components. When developing a sing page app, this will be an important capability as the UI can get complicated very quicly. 

Back End : 


1. I've never really used Node.js but interested in learning it, so I take this chance to learn it. It's fast and powerful. 
2. For the service, the are not many choices for node.js. Restify/Express both are light and handles a small application like this well. 
3. Require.js helps modularize all the files in the project which gives a good structure for the project to go forward. 
Database : 


1. In this project, there is bascially no database write required after the db get populated. And the data is only about 600 records in a json file. Therefore MongoDB is best choice as it's light but scalable, and it's object oriented which naturally maps our existing json data. 
Test : 


1. Mocha is good choice for Node.js and Backbone.js as it supports both node and browser. You can use any assertion style and well support for async testing. It also works well with other library such as sinon to provide stubs etc. All the test is also modularized with require.js. 

Trade-offs 
----------------------
Due to work, I have very very limited time to work on this. So in terms of functional, I would like to add the ability to rate and tag different food trucks, filter food trucks by food types and tags, and better UI improvement. Also, as it's my first time using the whole stack of technology, there are places that I need to learn more to find the best practice. I think if I had time I can go over the code and better refactor the code. For example, optimize the communication of different backbone components. 


Other Code that Worth A Look 
----------------------
Improved Movie Recommendation Engine 
GitHub Repo : https://github.com/chefandengineer/MovieRecommendationEngine
