# GmailOAuthReactDotnetCore

	1. https://console.developers.google.com/
	2. Oauth consent screen- give details: user type external. Add a test user for testing purposes. Can also give same in assignment while testing
	3. 
	4. Now go to credentials- and create oauth client ID (also see link in case of doubts below: https://medium.com/@alexanderleon/implement-social-authentication-with-react-restful-api-9b44f4714fa)
		a. App type: web application
		b. Authorizied Js login url: localhost:3000
	5. Click create and save the client ID and secret displayed
		a. Client ID: 297767953648-nt1pbfnp7v9nikqtqnafl15c05q4ium2.apps.googleusercontent.com
		b. Client secret: 4D0FN8QbNshHTjEHjGK5CjZk
	6. Lets create backend:
		a. Create a new folder called backend in ur system
		b. Open CMD- and navigate inside backend folder
		c. Execute "dotnet new webapi"- this will create the projcet
	7. Now add the below packages into the project (run in same CMD window, in same backend folder): 
	dotnet add package Google.Apis.Auth
	dotnet add package Newtonsoft.Json
	dotnet add package Serilog
	dotnet add package Serilog.Sinks.Console
	8. Now open the project is normal Vs or VS code
	9. Program.cs before change: 
	10. 
	11. Startup.cs before change:
	12. 
	13. In frontend folder, first run "npm install"
	14. npm run-script build
	15. npm start
