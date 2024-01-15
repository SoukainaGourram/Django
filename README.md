  # Django
. Django is a back-end server side web framework.
. Django is free, open source and written in Python.
. Django makes it easier to build web pages using Python.

  # How does Django Work?
  Django follows the MVT design pattern (Model View Template).
. Model - The data you want to present, usually data from a database.
. View - A request handler that returns the relevant template and content - based on the request from the user.
. Template - A text file (like an HTML file) containing the layout of the web page, with logic on how to display the data.
   ### Models:  
   Is the single, definitive source of information about your data. It contains the essential fields and behaviors of the data you’re storing. Generally, each model maps to a single database table.
The basics: .Each model is a Python class that subclasses django.db.models.Model.
            .Each attribute of the model represents a database field.
            .With all of this, Django gives you an automatically-generated database.

  ### Views:
  Django Views are one of the vital participants of MVT Structure of Django. As per Django Documentation, A view function is a Python function that takes a Web request and returns a Web response. This response can be the HTML contents of a Web page, or a redirect, or a 404 error, or an XML document, or an image, anything that a web browser can display. 
Django views are part of the user interface — they usually render the HTML/CSS/Javascript in your Template files into what you see in your browser when you render a web page. (Note that if you’ve used other frameworks based on the MVC (Model-View-Controller), do not get confused between Django views and views in the MVC paradigm. Django views roughly correspond to controllers in MVC, and Django templates to views in MVC.)

 ### Templates:
   A template in Django is basically written in HTML, CSS, and Javascript in a .html file. Django framework efficiently handles and generates dynamic HTML web pages that are visible to the end-user. Django mainly functions with a backend so, in order to provide a frontend and provide a layout to our website, we use templates. There are two methods of adding the template to our website depending on our needs.
We can use a single template directory which will be spread over the entire project. For each app of our project, we can create a different template directory.

# Features:
. ORM (Object-Relational Mapping): Django provides a powerful and flexible ORM, allowing you to interact with databases using Python classes and queries.
. Admin Interface: An automatically generated admin interface that enables easy content management.
. URL Routing: A clean and elegant URL routing system for handling HTTP requests.
. Template Engine: A template engine that encourages the separation of logic and presentation.
. Middleware: Allows you to process requests globally before they reach the view.
. Security: Built-in protection against common security threats like SQL injection, cross-site scripting, and cross-site request forgery.
. Authentication and Authorization: Provides a robust authentication system and flexible authorization controls.
. Reusable Apps: Encourages the creation of modular and reusable applications.

# Getting Started:
### Installation:




