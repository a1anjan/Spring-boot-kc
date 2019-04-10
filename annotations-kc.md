

@SpringBootApplication -

@RequestBody -
  The @RequestBody annotation maps the HttpRequest body to a transfer or domain object, 
  enabling automatic desialization of the inbound HttpRequest body onto a Java object.
  
  - It is used bind the HTTP request/response body with a domain object in method parameter or return type.
  
  - Spring will bind the incoming HTTP request body to that parameter. While doing that spring will use HTTP massage converter 
  to convert the HTTP request body into domain object, based on Accept header present in request.
  
 @ResponseBody -
  
  
  
  
