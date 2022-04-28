# how_the_web_works

-HTTP = Hypertext Transfer Protocol
-URL = Uniform Resource Locator, a URL is an address for some internet resource
-DNS = Domain Name System, takes readable URL's and converts them to IP addresses
-A query string allows you to pass key-value pairs into the URL, in the format (ie. ?key1=value1&key2=value2...)
-Two HTTP Verbs: 
	GET - retrieve data from a server
	POST - send some data to a server
-An HTTP request is a request from a client to a server which follows the HTTP protocol
-An HTTP response is a response from a server to a client which follows the HTTP protocol
- Headers provide additional information about the request or the response. Some examples are Content-Language, Content-Type, User-Agent, Accept
- What happens when you type a URL in a browser:
	-Your browser “resolves” the name into an IP address using DNS
	-Your browser makes a request to that IP address, including headers (info about browser, any previous cookies, and other things)
	-The server sends a response (typically, HTML, with a status code (200 if it was sucessful)
	-The browser makes a DOM from that HTML, and finds any other resources needed (images, CSS, JavaScript, etc)
	-The browser makes separate HTTP requests for those resources and receives response from the server for each
