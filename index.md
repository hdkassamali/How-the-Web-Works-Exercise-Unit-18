## Part One: Solidify Terminology
1. What is HTTP? HyperText Transfer Protocol. The way to make a request over the internet.
2. What is a URL? Uniform Resource Locator. The address of a website.
3. What is DNS? Domain Name System. A way for humans to access information online. Translates domain names to IP addresses.
4. What is a Query String? Parameters passed into a request to look for filter for specific information.
5. What are two HTTP vers and how are they different? GET and POST. Get is getting a request without changing information in the database. Post is making a request, but while changing information in the database.
6. What is an HTTP Request? A request is the process of sending a request to a server. The server will respond with an HTTP response.
7. What is an HTTP Response? A response is the process of receiving a response from a server. The server will respond with an HTTP response.
8. What is an HTTP header? Give a couple examples of request and response headers you have seen. Headers are used to identify the type of request and response. An example of a request header is Accept and an example of a response header is Content-Type.
9. What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser? The browser will first make a request to the server. The server will respond with an HTTP response. The browser will then display the response to the user. 

## Part Two: Practice Tools
1. Using curl, make a GET request to the icanhazdadjoke.com API to find all jokes involving the word “pirate”. curl -H "Accept: application/json" "https://icanhazdadjoke.com/search?term=pirate"
2. Use dig to find what the IP address is for icanhazdadjoke.com. dig icanhazdadjoke.com +short
3. Make a simple web page and serve it using python3 -m http.server. Visit the page in a browser. python3 -m http.server
   

