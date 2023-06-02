### How Spring MVC works?
    Client sends a request to web.xml, that request will go to Front Controller(Dispatcher servlet) from there it will go to particular controller (if we have many controllers). 
    We will put all the configurations in one file (Ex: abc-servlet.xml). This file will get the view page from the controllers.
    This XML file will not know how many controllers we have in backend. And Controllers don't know which view template we are using (EX: JSP, Thymeleaf, velocity, FreeMarker). 
