# HTML Request

An **HTML request** is a type of HTTP (Hypertext Transfer Protocol) request sent from a client, typically a web browser, to a server to retrieve or submit data. When you enter a URL in your browser or click a link, your browser sends an HTML request to the web server hosting the content, asking for specific resources (like HTML pages, images, or scripts). The server processes the request and sends back an HTTP response, which includes the requested content.

## Types of HTTP Requests

1. **GET**:
   - Requests data from a specified resource.
   - Commonly used to retrieve HTML pages, images, or other data without making any changes on the server.
   - **Example**: When you visit a webpage, your browser sends a GET request to fetch the HTML content.

2. **POST**:
   - Submits data to be processed to a specified resource.
   - Often used when submitting form data or uploading a file.
   - **Example**: When you fill out a contact form on a website and click "Submit," your browser sends a POST request with the form data.

3. **PUT**:
   - Updates a resource with new data.
   - Unlike POST, which creates a new resource or submits data, PUT replaces the current representation of the resource with the uploaded content.
   - **Example**: Updating a user's profile information.

4. **DELETE**:
   - Deletes the specified resource.
   - **Example**: Removing a user's account or a specific post on a website.

5. **HEAD**:
   - Similar to GET, but only requests the headers of a resource, not the actual content.
   - Useful for checking if a resource exists or retrieving metadata.

6. **OPTIONS**:
   - Describes the communication options for the target resource.
   - Often used in CORS (Cross-Origin Resource Sharing) requests to determine what methods are allowed for a resource.

7. **PATCH**:
   - Partially updates a resource.
   - Similar to PUT, but only changes part of the resource instead of replacing it entirely.

## Example of an HTTP GET Request

When you visit `https://www.example.com`, your browser sends an HTTP GET request like this:

```plaintext
GET / HTTP/1.1
Host: www.example.com
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/92.0.4515.107 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8
Accept-Encoding: gzip, deflate, br
Accept-Language: en-US,en;q=0.5
