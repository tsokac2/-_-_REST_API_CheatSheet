<h1 align="center">REST API CheatSheet</h1>


### REST
**Representational State Transfer**

**Main Features:**
- Easy to use and more flexible
- Shorter learning curve
- Efficient (uses smaller message formats like JSON)
- Fast - no extensive processing required
- Uses easy to understands Swagger and OpenApi Specification 3.0

**Basic REST API HTTP Requests are:**

|REST API HTTP Requests|       |
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