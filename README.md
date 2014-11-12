Java ReST Server
=========================

This simple server was developed using Spring and Gradle, taking guidance from the Spring tutorials.

Use
-----

The server will show the word `index` - nothing exciting. If you navigate to `/greeting` you will get a JSON object as a response to the GET request, showing the total number of requests to date, and a traditional message.

To personalize the message, add a URL parameter of `name` to the request.

The app (for what it's worth) is demoed on AWS here: http://default-environment-gmxr4xdapg.elasticbeanstalk.com/

To Do
-----

What's not to do?! This needs tests *everywhere*, and a much more interesing app sitting behind the API. And I'd like to learn how to use Hibernate to get this all to talk to a database.
