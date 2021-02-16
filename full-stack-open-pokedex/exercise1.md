Ive chosen Python as it's the first language I picked up taking an online course
 
 
Linting:
Interesting options from an article here https://realpython.com/python-code-quality/
They range from Logical, Stylistic, Analytical or all. Stylistic meaning that there is formatting for style which is perfect for readability, although this is less of an issue in Python than Javascript. Logical meaning syntax and error checking is implemented, similar to how Eslint is used for Javascript. Analytical seems to be a metric thing, checking for complexity and other things.
 
My choice would be Flake8 because it combines Stylistic, Logical, and Analytical linting.
 
Testing:
Another Real Python article, https://realpython.com/python-testing/#testing-your-code shows a different ecosystem of testing to Javascript. Assert functions are native to python and can be implemented for simple unit testing for any application. Packages are available on pip that manage bigger use cases. Assuming end to end testing would be supported with packages in frameworks like Django and Flask for python.
 
Building:
Documentation outlines how to handle packaging for builds here https://packaging.python.org/tutorials/packaging-projects/. It outlines how to use a build script setuptools, and how to manage folder structure for the application. 
 
 
Alternatives for CI/CD:
 
Using https://www.katalon.com/resources-center/blog/ci-cd-tools/ as reference, there are a few alternatives when it comes to CI/CD development.
 
CircleCI has some interesting integrations, builds in containers, and allegedly has easy debugging.
 
TeamCity is JetBrains program for CI/CD, few interesting features being history builds, pinning and tagging. User roles and grouping seems good for large organizations
 
Travis CI I've heard a few things about, its liked because of its quick setup and compatibility