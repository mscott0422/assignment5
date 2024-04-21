How to run code:

1. Clone the repo
2. Run mvn clean
3. Run mvn compile
4. Run mvn package
5. Right click the assignment5.war file --> Run on Server
6. Select your downloaded tomcat server

Notes: 
1. Make sure to change the default port in your server.xml file to something other than 8080. Then port-forward that port in vs-code and restart your server (if running already).
2. If your apache tomcat server doesn't say (Started) (Synchronized), you will need to remove the deployment (if you have one), restart the server, and re-add the deployment (.war file)
