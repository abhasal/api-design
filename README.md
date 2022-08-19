# api-design
This document is to help understand API Design concepts, REST API to be specific.


Representational State Transfer (REST)
- architectural style of designing web services
- independent of any underlying protocol and is not necessarily tied to HTTP.

What does REpresentational means
Clients and servers exchange representations of resources. For example, in a POST request, the request body contains a representation of the resource to create. In a GET request, the response body contains a representation of the fetched resource.

Below are critical items to consider while designing API.
1. Resource & Action (HTTP method)
2. Versioning
3. Security
4. Header params
5. Return codes
6. Pagination
7. Caching
8. Monitoring: health check URL

More to come...