<h1 align="center">REST API CheatSheet</h1>

### REST API
**Representational State Transfer**

**API** - Application programming interface
The client sends a request for specific information or functionality to another system.<br/>

_APIs: The Electric Current between software_


**Main Features:**
- Easy to use and more flexible
- Shorter learning curve
- Efficient (uses smaller message formats like JSON)
- Fast - no extensive processing required
- Uses easy to understands Swagger and OpenApi Specification 3.0

**Basic REST API HTTP Requests are:**

|REST HTTP Requests|       |
|--------|-------|
|GET | Read or retrieve data |
|POST | Add new data |
|PUT | Update already existing data - The whole data - entire resource |
|DELETE | DELETE - Remove Data |
|HEAD | Read Data - Must not return message - Body in the response |
|OPTIONS | What methods are allowed for this resource |
|PATCH | Updating/modifying - partial data of the resource - one part of the data - very attractive solution for public APIs |


**Conclusion:**
As one REST API tutorial put it:<br/>
_"SOAP is like an envelope while REST is just a postcard"_


### Difference between HTML and DHTML?
**HTML** - Hyper Text Markup Language
- Creates static web pages
- Creates simple plain pages - no **CSS** or **JS**
- Can not have any server-side code
- No need for database connectivity
- Files are stored with .htm or .html
```
<!DOCTYPE html>
<html>
    <head></head>
<body>
    <script></script>
</body>
</html>
```

**DHTML** - Dynamic Hypertext Markup Language
- DHTML creates dynamic web pages
- Creates a page with **HTML**, **CSS**, **DOM**, and a script called **DHTML**.
- May contain server-side code and also may require a connection to the database as it interacts with the user.
- Files are stored with the ```.dhtm``` extension.

### AJAX
**Asynchronous JavaScript and XML**
Used for the XMLHttpRequest object to communicate with the server.<br/>
Can send and receive info in various formats including JSON, XML, HTML, and text files.<br/>
Can send and retrieve data from a server asynchronously without interfering with the display and behavior of the existing page.

### URL
Uniform Resource Locator.
Web address - a reference to a web resource that specifies its location.

### URI
**Uniform Resource Identifier**
The unique sequence of characters that identifies logical or physical resources used by web technologies.

### Good pratices for URIs
- Globally unique
- Persistent
- Stabel - never re-used for different things
- Hierarchical structure
- Sense of Consistency


|Types of protocols|       |
|--------|-------|
|TCP  | Transmission Control Protocol |
|IP   | Internet protocol |
|UDP | User Datagram Protocol |
|FTP | File Transfer Protocol |
|HTTP | Hyper Text Transfer Protocol |
|HTTPS | Hyper Text Transfer Protocol Secure |
|SMTP | Simple Mail Transport Protocol - Email communication - Outgoing |
|POP | Post Office Protocol - POP3 - is designed for receiving incoming E-mails |
|TELNET | Connecting system to another system |


### Web Proxy Server
Is a gateway between a client application  - browser and the real server.<br/>
It makes a request to the real server on behalf of the client or sometimes fulfills the claim itself.

**Features:**
- Control internet access
- Privacy benefits
- Access to blocked sites
- Improved speed and bandwidth savings
- Improved security

### Bandwidth
The max amount of data transmitted over an internet connection in a given amount of time.<br/>
The volume of information sent.


### Benefits of APIs
- Outsourcing
- Increased Mobility
- Abstractions
- Increased Developer Productivity

#### Outsourcing
APIs allow you to outsource key data and functionality through a predictable standard interface.

#### Increased Mobility
Your software just needs to know how to connect to the other system not know how the other system works.

#### GraphQl - Facebook
Makes it possible to request information from across an entire graph of data at once - versus the multiple round trips of request, it takes traditional APIs to accomplish the same thing.

#### gRPC - Google
It relies on HTTP/2 (HTTP version 2) which can stream data bi-directionally.
Can turn an API into a streaming API that feeds its data to the consuming applications as soon as that data becomes available.


### Server errors

|Error|       |
|--------|-------|
|500 | Internal Server Error |
|403 | Forbidden |
|404 | Not Found |
|400 | Bad Request |
|401 | Unauthorized |

**More info:** https://en.wikipedia.org/wiki/List_of_HTTP_status_codes

### SOAP - Simple Object Access Protocol

**XML** - Extensible markup language - for sharing structured info between programs, and computers both locally and across networks.<br/>
XML is used in SOAP API

### SOAP
**Main Features:**
- Language, platform, and transport independent (REST uses HTTP).
- Standardized.
- Built-in error handling.
- Automation with certain languages.
- Relies heavily on XML - defines a very strongly typed messaging framework.
- Uses WSDL - Web Service Description Language  - a contract between the service provider and user.
- Can be sent over almost any protocol as HTTP, SMTP, TCP, or JMS.
- Must be XML - formatted  - must be one root element - contains two required elements - Header and Body - Header and Body.

WSDL - the contract between you(provider) and every single customer(consumer of the service).

**SOAP-ENV:** 

|Envelope|       |
|--------|-------|
|SOAP-ENV:|Header|
|SOAP-ENV:|Body  |


## API CORE CONCEPTS
- Setup workspaces
- Setup collections  - request collections
- Setup variables - global variables
- Query parameters
- Define requests - GET, PUT, PATCH, DELETE, POST
- Testing in Postman - testing snippets or custom JavaScript tests - CI/CD
- **CI/CD** -  **C**ontinuous **I**ntegration and **C**ontinuous **D**elivery or Continuous Deployment
- Collection runner
- Postman monitors
- Newman - CLI for the postman - generate HTML reports

**PSP** - Payment Service Providers <br/>
**PSD2** - Payments Service Derivative 2 <br/>
**PSP** - EX. Stripe

#
### Events

- **Definition**: Events are specific occurrences or actions that happen within a system or application.
- **Examples**: In a social media platform, an event could be a user posting a new message, liking a comment, or following another user. In an e-commerce platform, it could be an order being placed, a payment being processed, or an item being shipped.


### Webhooks

- **Definition**: Webhooks are a mechanism for notifying external applications about these events. They essentially act as messengers, delivering information about the event to a designated URL whenever it occurs.

**How they work**:

- **Subscription**: An application registers its URL with the system or service that generates events. This subscription signifies the application's interest in receiving notifications about specific events.

- **Event trigger**: When the subscribed event occurs within the system, a notification containing relevant information about the event is sent as an HTTP request (usually a POST request) to the registered URL.

- **Receiving and processing**: The receiving application at the other end of the URL can then process the information in the notification and take appropriate actions based on the event type.

#
### Fintech
Computer programs and other technologies used to support or enable banking and financial services.

## Authentication vs. Authorization

### Authentification
Process of verifying who is the user.

### Authorization
Process of verifying what they have access to.

### OAuth 2
In connection with "Authorization".<br/>
Service sharing resources on behalf of user/client/customer/person. <br/>
Connection is established with an access token specifically for that resource and not all resources.

### Resource
The thing that is shared between services.

### Resource owner
User can grant access to resources.

### Resources server
Google Drive, AWS

### Clinet - App
The App that requests access to user resources.

### Autorization server
The server issues an **Access Token** to the client.

### OAuth flows
- Authorization Code Flow
- Implicit Flow
- Client Credential Flow

### SSO
**Single sign-on**<br/>
Authentication method that enables users to securely authenticate with multiple applications and websites by using just one set of credentials.<br/>
If you log in to Google services such as Gmail, you are automatically authenticated to YouTube, Ad Sens, and Google Analytics.

### CURL Post
Command line tool and library for transforming data with URLs - install GIT Bash for curl post

**Popular curl Examples:** https://www.keycdn.com/support/popular-curl-examples

### Swagger
Open source API Documentation framework to help develops the design document and consume restful web services.<br/>
Reads an API and extracts in the form of interactive UI called as **Swagger UI**.

Swagger UI offers an HTML view of API with JSON Support.<br/>
A most popular tool for generating interactive documentation from API.