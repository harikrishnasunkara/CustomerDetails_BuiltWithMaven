# CustomerDetails_BuiltWithMaven

This is a mule Application which exposes a rest API to perform following operations :

	Page though the list of customers using offset and limit as query parameters
	search customers by post code
	search customer by customer ID
	
	While designing RAML 1.0 in design centre , I have used some best practises and used Libraries, traits and Data types. I have used H2 as in Memory Database
	The implementations also uses Cache scope to improve performance.
	Caching can be disabled by passing a query parameter bypasscache=true

To run this code please use the Mule server 3.8.5 EE.

Configuration XMLS:

1.Customersaerchapiusingresourcetypestraits.xml (API router process)
2.Customersearchapiimpl.xml (Implementation process of API)
3.Consumer.xml (Is for testing purpose)

The code is running and I have tested all the unit test cases successfully.
	 
This is a maven based mule project so, it will manage its dependencies.
As I have used enterprise edition to build maven repository it needs password so please use Enterprise edition password.
If it is not available then I have developed another flow with out maven and the same is uploaded to git hub.

Unit testing:

All the scenarios which are require to cover the use case are covered and the screen shots of the results were taken and attched 
in the github.
	 
MUnit tests are also included.

NOTE: If Username and Password incorrect issue exists while running the code then kindly do the following

1.Remove the username and password for the DB url in DB initialization
2.pelase comment the tag in the configuration xml of customersserachapiimpl.xml

