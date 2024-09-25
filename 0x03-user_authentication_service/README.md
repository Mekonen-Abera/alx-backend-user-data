# Project: 0x03. User authentication service

## Resources

#### Read or watch:

* [Flask documentation](https://intranet.alxswe.com/rltoken/lKExyvivrrW4eh0eI8UV6A)
* [Requests module](https://intranet.alxswe.com/rltoken/py7LuuD1u2MUwcaf8wnDzQ)
* [HTTP status codes](https://intranet.alxswe.com/rltoken/cj-mc5ZHp_KyXn1yikHC0A)

## Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

* How to declare API routes in a Flask app
* How to get and set cookies
* How to retrieve request form data
* How to return various HTTP status codes
### Requirements
* Allowed editors: vi, vim, emacs
* All your files will be interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7)
* All your files should end with a new line
* The first line of all your files should be exactly #!/usr/bin/env python3
* A README.md file, at the root of the folder of the project, is mandatory
* Your code should use the pycodestyle style (version 2.5)
* You should use SQLAlchemy 1.3.x
* All your files must be executable
* The length of your files will be tested using wc
* All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
* All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
* All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
* A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)
* All your functions should be type annotated
* The flask app should only interact with Auth and never with DB directly.
* Only public methods of Auth and DB should be used outside these classes

## Setup
* You will need to install bcrypt
* pip3 install bcrypt

## Tasks

| Task | File |
| ---- | ---- |
| 0. User model | [user.py](./user.py) |
| 1. create user | [db.py](./db.py) |
| 2. Find user | [db.py](./db.py) |
| 3. update user | [db.py](./db.py) |
| 4. Hash password | [auth.py](./auth.py) |
| 5. Register user | [auth.py](./auth.py) |
| 6. Basic Flask app | [app.py](./app.py) |
| 7. Register user | [app.py](./app.py) |
| 8. Credentials validation | [auth.py](./auth.py) |
| 9. Generate UUIDs | [auth.py](./auth.py) |
| 10. Get session ID | [auth.py](./auth.py) |
| 11. Log in | [app.py](./app.py) |
| 12. Find user by session ID | [auth.py](./auth.py) |
| 13. Destroy session | [auth.py](./auth.py) |
| 14. Log out | [app.py](./app.py) |
| 15. User profile | [app.py](./app.py) |
| 16. Generate reset password token | [auth.py](./auth.py) |
| 17. Get reset password token | [app.py](./app.py) |
| 18. Update password | [auth.py](./auth.py) |
| 19. Update password end-point | [app.py](./app.py) |
| 20. End-to-end integration test | [main.py](./main.py) |

## Done By: Mekonen Abera

