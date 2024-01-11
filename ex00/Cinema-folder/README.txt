


# Notes

=> Difference between servlets and controllers and when to use each ?

A Servlet and a Spring MVC Controller can be used to do the same thing but they act on different level of a Java Application

The servlet is a part of the J2EE framework and every Java application server (Tomcat, Jetty, etc) is built for running servlets. 
Servlet are the "low level" layer in the J2EE stack. You don't need a servlet.jar to run you application because it's prepackaged with the application server

A Spring MVC controller is a library built upon the servlet to make things easier. 
Spring MVC offers more built-in functionalities such as form parameter to controller method parameter mapping, 
easier handling of binary form submissions (i.e. when your form can upload files). 

You should use a servlet when you need to go "low level", and example could be for performance reason. 
Spring MVC performs good but if it has some overhead, if you need to squeeze out all you can from your application server 
(and you have already tuned the other layers such as the db) go with a servlet. 
You can choose a servlet if you want to understand the foundation of the J2EE web specifications (i.e. for educational purposes)








# Study
[ ] Spring MVC docs
[ ] JPA intro
