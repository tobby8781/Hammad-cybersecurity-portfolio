# How the Web Works & Web Security Fundamentals

## Overview

This section documents the web and security fundamentals I learned during the TryHackMe Pre Security learning path.

The focus was on understanding how users interact with websites, how web requests are handled, and how basic web technologies and security concepts fit together.

---

## 1. How the Web Works

The web allows users to access resources hosted on servers through browsers and other clients.

A typical interaction involves:

1. A user enters or follows a web address.
2. The browser identifies the destination.
3. DNS can resolve the domain name to an IP address.
4. The client communicates with the destination server.
5. The server processes the request.
6. The server returns a response.
7. The browser interprets the response and displays the result.

Understanding this request-and-response process is an important foundation for web security.

---

## 2. URLs

A URL (Uniform Resource Locator) identifies a resource on the web.

A URL can contain components such as:

- Scheme/protocol
- Domain
- Port
- Path
- Query parameters
- Fragment

Example:

`https://example.com/page?item=1`

Understanding URL structure helps when analysing web requests and investigating suspicious links.

---

## 3. HTTP and HTTPS

HTTP (Hypertext Transfer Protocol) is used for communication between web clients and servers.

HTTPS is HTTP protected using TLS.

The basic communication model is:

**Client → Request → Server → Response → Client**

### Security relevance

HTTPS helps protect data in transit by providing encryption and authentication through TLS.

---

## 4. HTTP Requests

A web client sends an HTTP request to a server.

Important request components include:

- HTTP method
- URL/path
- Headers
- Request body

Common HTTP methods include:

- GET
- POST
- PUT
- DELETE

### GET

GET is commonly used to request data or a resource.

### POST

POST is commonly used to submit data to a server.

---

## 5. HTTP Responses

A server returns an HTTP response to the client.

Important response components include:

- Status code
- Headers
- Response body

Status codes communicate the result of a request.

Examples include:

- 200 – successful request
- 301/302 – redirection
- 400 – client-side request error
- 403 – access forbidden
- 404 – resource not found
- 500 – server-side error

Understanding status codes is useful when troubleshooting websites and analysing web activity.

---

## 6. Web Servers

A web server receives and processes web requests and returns resources or responses to clients.

The client and server model is fundamental to web applications.

Security monitoring can involve examining requests and responses for unusual or malicious behaviour.

---

## 7. Web Technologies

Modern websites can use several technologies working together.

### HTML

HTML provides the structure and content of a webpage.

### CSS

CSS controls presentation and visual styling.

### JavaScript

JavaScript provides programming and interactive behaviour in web pages.

During the Pre Security learning, I also worked through basic JavaScript logic, including:

- Variables
- Conditions
- Loops
- Comparisons
- Random number generation

---

## 8. Client-Side and Server-Side Concepts

### Client-side

Client-side code runs in the user's browser.

JavaScript is commonly used for client-side functionality.

### Server-side

Server-side code runs on the web server and can handle application logic, authentication, data processing, and database interactions.

Understanding the difference is important when studying web application security.

---

## 9. Sessions

A session represents an established interaction between a client and a server.

Session concepts are important because web applications often need to maintain state between multiple requests.

Understanding sessions provides a foundation for later learning about authentication and web application security.

---

## 10. Web Security Foundations

The Pre Security material provides foundational knowledge that supports later study of web attacks and defences.

Important areas include:

- Understanding requests and responses
- Recognising HTTP methods
- Understanding URLs and parameters
- Understanding client-side JavaScript
- Understanding server-side processing
- Understanding sessions
- Recognising how browsers communicate with servers

These concepts are prerequisites for more advanced web security topics.

---

## 11. Practical Knowledge Gained

I practised and reviewed:

- Web request and response flow
- URLs
- HTTP and HTTPS
- HTTP methods
- HTTP status codes
- Web servers
- HTML
- CSS
- JavaScript
- Client-side vs server-side concepts
- Sessions
- Basic JavaScript logic

---

## Cybersecurity Relevance

Understanding how normal web communication works is essential before analysing malicious web activity.

These foundations will support future learning in:

- Web application security
- Web reconnaissance
- HTTP traffic analysis
- Authentication security
- Session security
- Vulnerability investigation
- Security monitoring

---

## Key Takeaways

- Web communication follows a client-server model.
- DNS can resolve a domain name before a client connects to the destination.
- HTTP defines communication between web clients and servers.
- HTTPS adds TLS protection to HTTP communication.
- HTTP requests contain methods, headers, and other request information.
- HTTP responses contain status codes, headers, and response data.
- HTML provides webpage structure.
- CSS controls presentation.
- JavaScript adds programming and interactivity.
- Sessions help applications maintain state across requests.
- Understanding normal web behaviour provides a foundation for web security.

**Status: Completed — TryHackMe Pre Security**
