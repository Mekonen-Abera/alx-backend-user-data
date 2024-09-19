# Project: 0x02. Session authentication

## Resources

#### Read or watch:

* [REST API Authentication Mechanisms - Only the session auth part](https://intranet.alxswe.com/rltoken/oofk0VhuS0ZFZTNTVrQeaQ)
* [HTTP Cookie](https://intranet.alxswe.com/rltoken/peLV8xuJ4PDJMOVFqk-d2g)
* [Flask](https://intranet.alxswe.com/rltoken/yrCaeZxNcpagOLh-0SVhwA)
* [Flask Cookie](https://intranet.alxswe.com/rltoken/QYfI5oW6OHUmHDzwKV1Qsw)
## Learning Objectives

### General

* What authentication means
* What session authentication means
* What Cookies are
* How to send Cookies
* How to parse Cookies 

## Requirements

### Python Scripts

* All your files will be interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7)
* All your files should end with a new line
* The first line of all your files should be exactly #!/usr/bin/env python3
* A README.md file, at the root of the folder of the project, is mandatory
* Your code should use the pycodestyle style (version 2.5)
* All your files must be executable
* The length of your files will be tested using wc
* All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
* All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
* All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
* A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)

## Tasks

| Task | File |
| ---- | ---- |
| 0. Et moi et moi et moi! | [api/v1/app.py](./api/v1/app.py), [api/v1/views/users.py](./api/v1/views/users.py) |
| 1. Empty session | [api/v1/auth/session_auth.py](./api/v1/auth/session_auth.py), [api/v1/app.py](./api/v1/app.py) |
| 2. Create a session | [api/v1/auth/session_auth.py](./api/v1/auth/session_auth.py) |
| 3. User ID for Session ID | [api/v1/auth/session_auth.py](./api/v1/auth/session_auth.py) |
| 4. Session cookie | [api/v1/auth/auth.py](./api/v1/auth/auth.py) |
| 5. Before request | [api/v1/app.py](./api/v1/app.py) |
| 6. Use Session ID for identifying a User | [api/v1/auth/session_auth.py](./api/v1/auth/session_auth.py) |
| 7. New view for Session Authentication | [api/v1/views/session_auth.py](./api/v1/views/session_auth.py), [api/v1/views/__init__.py](./api/v1/views/__init__.py) |
| 8. Logout | [api/v1/auth/session_auth.py](./api/v1/auth/session_auth.py), [api/v1/views/session_auth.py](./api/v1/views/session_auth.py) |
| 9. Expiration? | [api/v1/auth/session_exp_auth.py](./api/v1/auth/session_exp_auth.py), [api/v1/app.py](./api/v1/app.py) |
| 10. Sessions in database | [api/v1/auth/session_db_auth.py](./api/v1/auth/session_db_auth.py), [api/v1/app.py](./api/v1/app.py), [models/user_session.py](./models/user_session.py) |

## Author's: Mekonen Abera
