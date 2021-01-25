# how-the-web-works
Exercises for Section 14.1

## Part One
- HTTP is hypertext trasfer protocol. It is a defined way to convey information on the world wide web.
- A URL is a universal resource locator. It identifies both the identity of the servers to be communicated with (e.g., google.com) and the specific files or information (e.g., a specific page and/or a query string).
- DNS is a domain name system. It matches an IP (internet protocol) address with letters that are (usually) more easily remembered (e.g., google.com).
- A query string comes after a '?' in the URL and identifies parameters specific to the request. It commonly involves search terms or identifying information.
- HTTP requests are usually 'GET' requests that only ask for a response from the servers and change nothing on the server. 'POST' requests send information to be added to the serverand are typically submitted through forms on webpages.
- An HTTP request is a communication via HTTP (hypertext transfer protocol) to a server (or group of servers) at the identified domain name reuesting a response defined by the rest of the URL.
- An HTTP response is the response returned by the server that received the request, also using HTTP. It is often in the form of an HTML webpage.
- an HTTP header gives information about the request or the response. Request headers include, for example, the prefered language for the response ('Accept-Language') and acceptable response types ('Accept') such as 'text/html. Response headers give, for example, the size of the response ('Content-length'), the response type ('Content-type) such as 'text/html', and the date and time of the response.
- When you type a URL into a browser, the browser forst checkes if it already has a copy of the page requested in its cache and renders it if so. If not, it goes out to find it using the domain name in the URL. The domain names can be matched with its IP address at several places, including the browser's cache, the router, the internet service provider, and special servers called DNS servers that hold the master lists matching domain names with their IP addresses. Once the IP adderss is known, the request (with all pertinent headers) goes to the servers identified by the domain name. Those servers interpret the headers and send a response back tot he browser with various headers and, if all went well, the requested web page.

## Part 2
1. curl -v https://icanhazdadjoke.com/search?term=pirate. (Sample: What does a pirate pay for his corn? A buccaneer!)
2. An IP address shows up in the curl response: 172.67.181.69. The dig response give two IP addresses: 104.21.91.232 and 172.67.181.69.
3. (Done)

## Part 3
1. 
