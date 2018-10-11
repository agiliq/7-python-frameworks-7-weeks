Django Overview
---------------


What is Django?
++++++++++++++++

    * Django is a free open-source web framework, written in Python, which follows the model-view-template(MVT) architectural pattern. It is maintained by Django Software Foundation(DSF). Django's primary goal is to ease the creation of complex, database-driven websites.
    * Django is a high-level Python Web framework that encourages rapid development and clean, pragmatic design. Built by experienced developers, it takes care of much of the hassle of Web development, so you can focus on writing your app without needing to reinvent the wheel.


Django Features:
+++++++++++++++++++++

    #. Fast
    #. Code Reusability
    #. Security
    #. Scalable
    #. Versatile
    #. Documentation
    #. Community


Inside Django
+++++++++++++++++++

    * **Django Philosophy**

    The web framework for perfectionists with deadlines.

    * **Django Architecture**

    Django follows the MVC pattern closely, however it does use its own logic in the implementation. Because the “C” is handled by the framework itself and most of the excitement in Django happens in models, templates and views, Django is often referred to as an MTV framework.

    * **Django ORM**

    ORMs provide a high-level abstraction upon a relational database that allows a developer to write Python code instead of SQL to create, read, update and delete data and schemas in their database. Developers can use the programming language they are comfortable with to work with a database instead of writing SQL statements or stored procedures.

    * **DRY principle**

    To help developers adhere to the DRY principle, Django forces users to use the MVC code structure. Django forces users to use this format by initially creating a views.py, models.py, and template files. By keeping the controller code separate from the views, it allows multiple controllers to use the same view.

    * **Loose coupling**

    A fundamental goal of Django’s stack is loose coupling and tight cohesion. The various layers of the framework shouldn’t “know” about each other unless absolutely necessary.

    For example, the template system knows nothing about Web requests, the database layer knows nothing about data display and the view system doesn’t care which template system a programmer uses.

    * **Request-Response cycle**

    Django uses request and response objects to pass state through the system.

    When a page is requested, Django creates an HttpRequest object that contains metadata about the request. Then Django loads the appropriate view, passing the HttpRequest as the first argument to the view function. Each view is responsible for returning an HttpResponse object.

    * **Middleware**

    Middleware is a framework of hooks into Django’s request/response processing. It’s a light, low-level “plugin” system for globally altering Django’s input or output.

    * **Template tags**

    Django’s template language comes with a wide variety of built-in tags and filters designed to address the presentation logic needs of your application.