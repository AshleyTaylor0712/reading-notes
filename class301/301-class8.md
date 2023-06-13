# Class 08 Reading Notes

### REST

- Representational State Transfer.
- Provides guidlines for web services and networked applications.
- REST APIs are designed around resources with the benefits of scalability & flexibility.

### Identifier Resoure

- Used to access and identify a specific resouce in a system
- Example: URL

### HTTP Verbs

- GET: Retrieves data from server without modifying
- POST: Submits data to server to create new resource
- PUT: Modifies state/props of a resource
- DELETE: removes a server resource
- PATCH: Updates resource fields

### URIs

- Represent objects that clients can interact with.
- Based on resources exposed by the API.
- URI Example: /books/9781234567890; represents an individual book and its ISBN 

### Chatty Web API

- A "chatty" web API refers to an API design where a client needs to make multiple requests, often a high number of small or granular requests, to accomplish a single logical operation or retrieve a desired set of data. Each request only fetches or modifies a small piece of information.
- Pros: Flexibility, Efficiency with large data sets
- Cons: Network Overhead, Reduced efficiency with small data sets, Increased Complexity

### What status code does a successful GET request return?

- 200 OK

### What status code does an unsuccessful GET request return?

- Status Code is the 4xx or 5xx range indicates an error or failure

### What status code does a successful POST request return?

- 201 Created

### What status code does a successful DELETE request return?

- 204 No Content
