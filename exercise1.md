# Exercise 11.1: Continuous Integration with Python 

Python code can be analysed by Pylint. It is a free software and has typical properties of a linter: it looks for programming errors, helps enforcing a coding standard, sniffs for code smells and offers simple refactoring suggestions. 

Unittest and Pytest  libraries are common tools for unit testing Python code. Unittest is built into the Python standard library. Beahavior driven testing is easy with Pytest-BDD that is plugin for Pytest and uses Gherkin language as usual.

In Python build step is not needed because it is interpreted language, so the CI with Python conserns test execution, creating virtual environment and installing dependencies rather than compilation.

CircleCI and TravisCI are commonly used alternatives to Jenkins and GitHub Actions. For example CircleCI can be used in the cloud or as a self-hosted in the environments of Linux, Mac or Windows. 

Cloud-based environments are almost always easier for the developer but eventually it depends on the application and the team whether the setup should be in a self-hosted or a cloud-based environment. In a self-hosted environment more hardware and more hardware maintanence is needed (although there are helpful tools for the self-hosting too). On the other hand the code is definitely safe and the team has full control over it. 








