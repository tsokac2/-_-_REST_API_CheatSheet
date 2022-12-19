<h1 align="center">REST API CheatSheet</h1>


### SOAP - Simple Object Access Protocol


### REST - Representational State Transfer

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

|Envelope|
|--------|
|SOAP-ENV:|Header|
|SOAP-ENV:|Body|