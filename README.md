## Advanced Python

Python is a dynamically-typed language. That means that variable types are dynamically set at run-time, upon assignment of a value to a variable.

In Python 3, Python is still a dynamically-typed language. Type annotations serve the following purpose:

- Code documentation: thanks to them, a developer reading type-annotated code (his own or someone elses) will know exactly what type each variables is supposed to be. This helps reduce bugs and exceptions and accelerate the development cycle.
- Linting and validation: code editors and continuous integration (CI) pipelines can be configured to automatically validate type-annotated code at build-time and catch bugs before they make it to production.
