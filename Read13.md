# Sending from Data

- The *action* attribute specifies where to send the form-data when a form is submitted. 

- The *method* attribute specifies how to send form-data (the form-data is sent to the page specified in the action attribute).

## The GET method ..
- The GET method is the method used by the browser to ask the server to send back a given resource: “Hey server, I want to get this resource.” In this case, the browser sends an empty body. Because the body is empty, if a form is sent using this method the data sent to the server is appended to the URL.

## The POST method ..
- The POST method is a little different. It’s the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request: “Hey server, take a look at this data and send me back an appropriate result.” If a form is sent using this method, the data is appended to the body of the HTTP request.

