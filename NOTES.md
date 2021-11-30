## REST API

REpresentational State Transfer (REST) refers to a group of software architecture design constraints that bring about efficient, reliable, and scalable systems. 

### The six constraints of REST

1. Client-server architecture- The clinet manages user interface concerners while the server manages data storage concerns. 
2. Statelessness - No client context or information aka "state", can be stored on the server between requests.
3. Cacheability - All REST responses must be clearly marked as cacheable or not cacheable. 
4. Layered system - The client cannot know, and shouldn't care, whethere it's connected directly to the server or to an intermediary like a CDN or mirror. 
5. Code on demand - Servers are allowed to transfer executable code like JavaScript and compiled components to clients.
6. Uniform interface - Breaks down into 4 more constraints. 
      - Resource indentification in requests - The URI request must specify what resource it is looking for and what format the response should use.
      - Resource manipulation through representations - Once a client has a representation of a resource, it can modify or delete the resource.
      - Self-descriptive messages - Data format should be informed. JSON for JSON for instance.
      - Hypermedia as the engine for application state - Once a client has access to a rest service, it should be able to discover all available resource and methods through the hyperlinks provided. 
