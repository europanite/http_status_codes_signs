# http_status_codes_journey
HTTP Status Code Images from Japanese Road Signs.

## 1xx — Informational
| Code | Reason Phrase                 | Description                              | Image | Adress | GPS |
| ---: | ------------------- | -------------------------------------------------- | --- | --- | --- |
|  100 | Continue            | Client should continue the request.                |  |  |  | 
|  101 | Switching Protocols | Server is switching protocols as requested.        |  |  |  | 
|  102 | Processing (WebDAV) | Server has received and is processing the request. |  |  |  | 
|  103 | Early Hints         | Hints the client to preload resources.             |  |  |  | 

## 2xx — Success
| Code | Reason Phrase                 | Description                                          | Image | Adress | GPS |
| ---: | ----------------------------- | ---------------------------------------------------- | --- | --- | --- |
|  200 | OK                            | Request succeeded.                                   |  |  |  | 
|  201 | Created                       | Resource created successfully.                       |  |  |  | 
|  202 | Accepted                      | Request accepted for processing, not completed.      |  |  |  | 
|  203 | Non-Authoritative Information | Returned meta-info may be from a transforming proxy. |  |  |  | 
|  204 | No Content                    | Success, no response body.                           |  |  |  | 
|  205 | Reset Content                 | Tell client to reset the document view.              |  |  |  | 
|  206 | Partial Content               | Partial response due to range header.                |  |  |  | 
|  207 | Multi-Status (WebDAV)         | Multiple status codes for multiple operations.       |  |  |  | 
|  208 | Already Reported (WebDAV)     | Members of a DAV binding already reported.           | !["208"](./assets/images/208.jpg) |  |  | 
|  226 | IM Used                       | Instance manipulations applied to the instance.      |  |  |  | 

## 3xx — Redirection
| Code | Reason Phrase                 | Description                    | Image | Adress | GPS |
| ---: | ----------------------------- | ------------------------------ | --- | --- | --- |
|  300 | Multiple Choices   | Multiple representations available.       |  |  |  | 
|  301 | Moved Permanently  | Resource moved permanently.               |  |  |  | 
|  302 | Found              | Resource temporarily under different URI. |  |  |  | 
|  303 | See Other          | Get resource at another URI with GET.     |  |  |  | 
|  304 | Not Modified       | Resource not modified since last request. |  |  |  | 
|  305 | Use Proxy          | **Deprecated.** Must use proxy.           | !["305"](./assets/images/305.jpg) |  |  | 
|  306 | (Unused)           | Reserved; no longer used.                 |  |  |  | 
|  307 | Temporary Redirect | Same method, different temporary URI.     |  |  |  | 
|  308 | Permanent Redirect | Same method, different permanent URI.     |  |  |  | 

## 4xx — Client Errors
| Code | Reason Phrase                   | Description                                             | Image | Adress | GPS |
| ---: | ------------------------------- | ------------------------------------------------------- | --- | --- | --- |
|  400 | Bad Request                     | Malformed syntax or invalid request.                    |  |  |  | 
|  401 | Unauthorized                    | Authentication required or failed.                      |  |  |  | 
|  402 | Payment Required                | Reserved for future use.                                | !["402"](./assets/images/402.jpg) |  |  | 
|  403 | Forbidden                       | Server understood but refuses to authorize.             | !["403"](./assets/images/403.jpg) |  |  | 
|  404 | Not Found                       | Resource not found.                                     | !["404"](./assets/images/404.jpg) |  |  | 
|  405 | Method Not Allowed              | Method not allowed for the target.                      | !["405"](./assets/images/405.jpg) |  |  | 
|  406 | Not Acceptable                  | No acceptable representation found.                     | !["406"](./assets/images/406.jpg) |  |  | 
|  407 | Proxy Authentication Required   | Authenticate with proxy first.                          | !["407"](./assets/images/407.jpg) |  |  | 
|  408 | Request Timeout                 | Server timed out waiting for request.                   | !["408"](./assets/images/408.jpg) |  |  | 
|  409 | Conflict                        | Request conflicts with current state.                   | !["409"](./assets/images/409.jpg) |  |  | 
|  410 | Gone                            | Resource permanently removed.                           |  |  |  | 
|  411 | Length Required                 | Content-Length header required.                         |  |  |  | 
|  412 | Precondition Failed             | One or more preconditions failed.                       |  |  |  | 
|  413 | Content Too Large               | Request payload is too large.                           |  |  |  | 
|  414 | URI Too Long                    | URI is too long to process.                             |  |  |  | 
|  415 | Unsupported Media Type          | Unsupported payload media type.                         | !["415"](./assets/images/415.jpg) |  |  | 
|  416 | Range Not Satisfiable           | Requested range cannot be served.                       | !["416"](./assets/images/416.jpg) |  |  | 
|  417 | Expectation Failed              | Expect header requirements not met.                     | |  |  | 
|  418 | I’m a Teapot                    | April Fools’/novelty; non-standard in practice.         | !["418"](./assets/images/418.jpg) |  |  | 
|  421 | Misdirected Request             | Request routed to a server that can’t produce response. |  |  |  | 
|  422 | Unprocessable Content (WebDAV)  | Well-formed but semantically erroneous.                 |  |  |  | 
|  423 | Locked (WebDAV)                 | Resource is locked.                                     |  |  |  | 
|  424 | Failed Dependency (WebDAV)      | Failed due to earlier request failure.                  |  |  |  | 
|  425 | Too Early                       | Risk of replay; try later.                              |  |  |  | 
|  426 | Upgrade Required                | Must upgrade protocol (e.g., TLS/HTTP2).                |  |  |  | 
|  428 | Precondition Required           | Preconditions required on the request.                  |  |  |  | 
|  429 | Too Many Requests               | Rate limit exceeded.                                    |  |  |  | 
|  431 | Request Header Fields Too Large | Header fields too large.                                |  |  |  | 
|  451 | Unavailable For Legal Reasons   | Blocked for legal demands.                              |  |  |  | 

## 5xx — Server Errors
| Code | Reason Phrase                   | Description                                      | Image | Adress | GPS |
| ---: | ------------------------------- | ------------------------------------------------ | --- | --- | --- |
|  500 | Internal Server Error           | Generic server error.                            |  |  |  |
|  501 | Not Implemented                 | Method not supported by server.                  |  |  |  | 
|  502 | Bad Gateway                     | Invalid response from upstream server.           |  |  |  | 
|  503 | Service Unavailable             | Temporarily overloaded or maintenance.           | !["503"](./assets/images/503.jpg) |  |  | 
|  504 | Gateway Timeout                 | Upstream server timed out.                       |  |  |  | 
|  505 | HTTP Version Not Supported      | HTTP version not supported.                      |  |  |  | 
|  506 | Variant Also Negotiates         | Content negotiation configuration error.         |  |  |  | 
|  507 | Insufficient Storage (WebDAV)   | Server cannot store the representation.          |  |  |  | 
|  508 | Loop Detected (WebDAV)          | Infinite loop detected in processing.            |  |  |  | 
|  510 | Not Extended                    | Further extensions required.                     |  |  |  | 
|  511 | Network Authentication Required | Client must authenticate to gain network access. |  |  |  | 
