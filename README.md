# CustomerDetails_BuiltWithMaven

This is a mule Application which exposes a rest API to perform following operations :

	Page though the list of customers using offset and limit as query parameters
	search customers by post code
	search customer by customer ID
	
	While designing RAML, I have used some best practises and used Libraries, traits and Data types. I have used H2 as in Memory Database
	The implementations also uses Cache scope to improve performance.
	Caching can be disabled by passing a query parameter bypasscache=true
	 
This is a maven based mule project so, it will manage its dependencies.
As I have used enterprise edition to build maven repository it needs password so please use Enterprise edition password.
If it is not available then I have developed another flow with out maven and the same is uoloade3d to git hub.

Unit testing:

All the scenarios which are require to cover the use case are covered and the screen shots of the results were taken and attched 
in the github.
	 
MUnit tests are also included.
