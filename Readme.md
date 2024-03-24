<h1>What is REST?</h1>
REST, which stands for Representational State Transfer, <br>
is the most popular architectural style for building APIs. <br>
In a RESTful architecture, resources are identified by URIs (Uniform Resource Identifiers), <br>
and operations are performed on those resources using a standard set of HTTP methods. <br>
Resources are represented in JSON or XML, <br>
which is transferred between the client and server in the HTTP request and response bodies<br>

<h1> What is gRPC? </h1>
gRPC is an open source, high-performance framework that facilitates efficient communication in distributed systems.<br>
gRPC is an implementation of the RPC (Remote Procedure Call) protocol,<br>
which enables services to call functions on other machines as if they were local software methods.<br>


<h1> Key similarities: gRPC vs REST </h1> 
* A client/server architecture <br>
* Use of HTTP <br>
* Support for many programming languages <br>
* Statelessness <br>


<h1> Differences </h1>
<image src="/pictures/gRPCvsREST.jpg">
<h1>When to use gRPC vs. REST </h1>
Rest : REST is therefore the ideal choice if you need to create a public API, <br>
	   as developers at other organizations will be able to easily integrate it into their own applications.<br>

gRPC : better suited than REST for microservice-based architectures, <br>
	   in which individual services may be developed in different programming languages and may face varying workloads. <br>
	   Additionally, gRPC’s use of Protobuf for binary data serialization makes it the better choice for applications that demand low latency and high throughput, <br>
	   while its support for different streaming patterns make it ideal for real-time chat and video applications<br>