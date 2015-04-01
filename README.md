# Advanced-Python-demos
What you will learn in this course

 Python has often been thought of as clean scripting language or a simple language to glue ‘real’ applications together. This view is completely out of sync with the real possibilities of the Python language. This course will show you the true power of the language and the ecosystem. You will see that entire high-performance application stacks can be build in Python.

You will learn to build rich MVC-based web applications with Pyramid. You will see a variety of ways to access relational databases from direct SQL all the way up to rich ORMs such as SQLAlchemy. You will learn about accessing popular NoSQL, document-databases with MongoDB, PyMongo, and MongoKit. You will build redistributable Windows-based EXEs that do not depend upon Python being installed on the target system. Finally, you will see how to test all these applications to keep them running correctly.

Course outline and topics

Day 1 

Lightning Review of Python Language
In this lesson, we will do a quick review of the Python language. While many students will have experience with the Python language, ensuring that everyone has a solid understanding of all the language features will serve the class well as we delve into deeper topics. We review basic Python programs, collections, functions, classes, and iteration among other topics.


File I/O
Working with files is fundamental to any programming language. Python has rich support for working with files including simple utility methods to load all data as well as more efficient streaming APIs. Beyond reading and writing text or bytes, we will explore intrinsic support for common file formats (JSON and XML) as well as object serialization via pickle. Finally, we look at two classes which provide access to files, directories, and more: os and sys.

Pythonic / Idiomatic Python
To say that code is Pythonic is to say that it uses Python idioms well, that it is natural or shows fluency in the language, that it conforms with Python's minimalist philosophy and emphasis on readability. There are both tools and techniques which help you write more Pythonic code and we will cover them in this lesson. We start by looking at the recommended code styles and conventions. We will also cover the code analysis tool PyLint.

Day 2

Database access (Relational)
Almost all applications depend on data in databases (either RDBMSes or NoSQL DBs). This lesson on accessing relational databases from Python will introduce database programming in Python. You will learn about working with the Python DB-API. We discuss connecting to databases, querying data, iterating over cursors, as well as updating data. Finally you will see how to handle the various database errors that arise when working with the API.

Database access via SQLAlchemy (Core model)
SQLAlchemy is the Python SQL toolkit and Object Relational Mapper (ORM) that gives application developers the full power and flexibility of SQL. It provides a full suite of well known enterprise-level persistence patterns, designed for efficient and high-performing database access, adapted into a simple and Pythonic domain language. In this module we will explore SQLAlchemy and learn to leverage its Core data model (sitting between raw SQL and the ORM) to build data-driven applications.

Database access via SQLAlchemy (ORM model)
SQLAlchemy provides a world-class ORM (Object-Relational Mapper) which builds upon its general Core programming model. In this session we will see how to map objects and classes to tables. How to customize the tables with things like uniqueness constrains, default values, and relationships between classes. You will see how to express queries in terms of Python objects and classes as well as map classes to and from tables with ease using SQLAlchemy’s ORM.

Day 3

Database access (NoSQL / MongoDB)
Almost all applications depend on data in databases (either RDBMSes or NoSQL DBs). This lesson on accessing NoSQL databases from Python will show you not only how but why you want to work with NoSQL databases in Python. Because we want to have hands-on demonstrations of all techniques in this course, we will choose a specific NoSQL database to work with: MongoDB, the most popular NoSQL database. We start by giving you a brief introduction to NoSQL and MongoDB before quickly moving on to the MongoDB Python API: PyMongo. We will discuss object serialization, reading existing data, writing and updating data among other topics you will need to be successful with MongoDB from Python.

Real world MongoDB with MongoEngine
Python and PyMongo allow direct programming against MongoDB from Python. This is most appropriately compared to programming at the level of raw SQL for RDBMSes.  That level is a necessary building block, but for most applications working at a higher level and building upon custom classes is more appropriate. This module explores one of the most popular ODMs (object-data mappers) for Python and MongoDB: MongoEngine. You will learn to build out your data model in rich classes and map them to and from MongoDB with ease and incredible performance.

Building redistributables (modules and packages)
Python has several mechanisms of redistributing reusable libraries and classes and building and working with these is what this lesson is all about. You will learn the difference between modules and packages. We will be creating packages and export types from them using __init__.py. We will discuss when and how you can convert large modules into packages for maintainability. There are some simple steps to take to make your script both directly executable and usable via a module. Finally, we will cover deploying applications including topics such as py2exe, pre-compiled python .pyc files, and pyinstaller.

Day 4

Web applications in Python (Pyramid)
There are several very popular and successful web frameworks in Python including Pyramid, Flask and Django. This course covers Pyramid for building web applications and services as we believe it offers greater flexibility to choose your building blocks (NoSQL vs. SQL databases, services, views, etc.) relative to Django. Pyramid is what is known as a micro web framework. It comes with "batteries included" but doesn't make any assumptions about the components of your site. Popular sites created with Pyramid include Dropbox, reddit, and digg.

Real-world Pyramid: layouts, controllers, and forms
After introducing Pyramid in the previous module, we move on to focus on real-world Pyramid applications. We will discuss various techniques needed to be successful with Pyramid. We will cover how to define a common look-and-feel for your site in a single, centralized location using layouts. You will learn about a more general way to define routes and group common request processing using Pyramid Handlers (AKA Controllers). Finally, you will create dynamic input forms which accept user-input and provide rich error feedback on invalid data.

Building RESTful and HTTP-based web services in Python
Python and Pyramid offer fantastic support for building both client-side and server-side web service components. In this module you will learn to build powerful HTTP clients and services that exchange data in JSON (and other formats).

Debugging and unit testing Python
This lesson is all about building reliable code and tracking down any errors that may slip through. We start off discussing unit testing in Python using PyUnit and py.test. You will learn to assert conditional statements to verify correct behaviors as well as test for errors and exceptions. Then we will move on to debugging. First we will cover basic debugging with pdb, IDLE, and pudb. Then we will move on to debugging in the IDEs (PyCharm, Eclipse, Visual Studio).
