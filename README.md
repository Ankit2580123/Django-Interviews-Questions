 # Django-Interviews-Questions
A curated collection of Django interview questions that I encountered during my interviews. This repository includes a mix of fundamental, advanced, and practical questions, making it a valuable resource for anyone preparing for Django-related job interviews. Perfect for brushing up on key concepts and gaining insights into frequently asked topics.

### 1) Explain Django.
- Django is a high level python web frameworks that are used to build scalable web application in less time, because its provides a lots of builtin features like `ORM`, `Authentications`,`middleware`,`Admin Panel` and many more.
- It is a server-side web framework that provides rapid development of secure and maintainable websites.

### 2) Which architectural pattern does Django follow?
- Django follows Model-View-Template (MVT) architectural pattern.
- Model:
Represents the data layer of the application.
Defines the database schema and handles data manipulation.
Interacts with the database through Django's Object-Relational Mapping (ORM).

- Template:
Handles the presentation layer.
Defines how data is presented to the user using HTML files combined with Django's template language.
Provides dynamic content rendering by integrating context data from views.

- View:
Acts as the business logic layer, bridging Models and Templates.
Processes user requests, retrieves data from models, and passes it to templates for rendering.
Returns the final HTTP response to the user.

### 3) What are the features available in Django web framework?
- Features available in Django web framework are:
- `Admin Interface (CRUD)`,`Templating`,`Form handling`,`Internationalization`,`A Session`, `user management`, `role-based permissions`,`Object-relational mapping (ORM)`,`Testing Framework`,`Fantastic Documentation`
