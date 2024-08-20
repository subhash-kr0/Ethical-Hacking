# HTML Response

An **HTML response** is the reply sent by a web server to a client (such as a web browser) after receiving an HTTP request. When a browser requests a resource (like a web page) via an HTTP request, the server processes the request and sends back an HTTP response. This response typically contains the status of the request, headers with metadata, and the requested content, which is often an HTML document.

## Key Components of an HTML Response

1. **Status Line**:
   - Indicates the outcome of the HTTP request.
   - Includes the HTTP version, a status code, and a status message.
   - **Example**: `HTTP/1.1 200 OK`
     - `200 OK` means the request was successful, and the server is sending back the requested resource.

2. **Response Headers**:
   - Contains metadata about the response.
   - Includes information like the content type, content length, server type, and caching policies.
   - **Example**:
     ```plaintext
     Content-Type: text/html; charset=UTF-8
     Content-Length: 348
     Server: Apache/2.4.1 (Unix)
     ```

3. **Response Body**:
   - The actual content requested by the client.
   - For an HTML response, this would typically be the HTML document that the browser will render.
   - **Example**:
     ```html
     <!DOCTYPE html>
     <html lang="en">
     <head>
         <meta charset="UTF-8">
         <title>Example Page</title>
     </head>
     <body>
         <h1>Hello, World!</h1>
         <p>This is an example HTML page.</p>
     </body>
     </html>
     ```

## Example of an HTTP Response

When a browser requests a page from `https://www.example.com`, the server might send back a response like this:

```plaintext
HTTP/1.1 200 OK
Content-Type: text/html; charset=UTF-8
Content-Length: 348
Server: Apache/2.4.1 (Unix)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Example Page</title>
</head>
<body>
    <h1>Hello, World!</h1>
    <p>This is an example HTML page.</p>
</body>
</html>
