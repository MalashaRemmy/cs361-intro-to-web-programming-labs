# Lab 02 — HTTP Request & Response Cycle

## Introduction

This lab explored how web browsers communicate with servers using the HTTP protocol.

Using browser developer tools, I inspected network requests and responses to better understand how webpages, images, stylesheets, scripts, and other resources are transferred across the web.

---

## Objectives

- Understand the HTTP request-response cycle
- Inspect browser network activity
- Analyse HTTP headers and status codes
- Understand how browsers retrieve web resources
- Explore how websites load multiple assets dynamically

---

## Concepts Covered

### HTTP

HTTP (HyperText Transfer Protocol) is the communication protocol used between clients and web servers on the World Wide Web.

### Client-Server Model

The browser acts as the client by sending requests to servers, which process the request and return responses.

### HTTP Requests

Requests sent by browsers may include:
- request method
- URL
- headers
- cookies
- query parameters

### HTTP Responses

Responses from servers contain:
- status codes
- response headers
- content/data
- caching instructions

---

## Practical Activities

- Opened Chrome DevTools Network tab
- Reloaded websites while monitoring requests
- Inspected request headers
- Inspected response headers
- Observed status codes such as:
  - 200 OK
  - 404 Not Found
  - 301 Redirect
- Analysed loading behaviour of CSS, JavaScript, and image assets

---

## Key Observations

One important observation from this lab was that loading a single webpage actually triggers many separate HTTP requests.

For example:
- the HTML document,
- CSS files,
- JavaScript files,
- fonts,
- images,
- and API calls

may all be requested independently by the browser.

This demonstrated how modern websites are composed of multiple interconnected resources rather than a single file.

---

## Lessons Learned

This lab provided a clearer understanding of how browsers and servers communicate internally.

Understanding HTTP communication is important for:
- frontend development,
- backend development,
- debugging,
- API integration,
- web security,
- and performance optimisation.
