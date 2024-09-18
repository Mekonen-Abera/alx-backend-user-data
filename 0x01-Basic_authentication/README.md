# Project: 0x01. Basic authentication

## Resources

#### Read or watch:

* [REST API Authentication Mechanisms](https://intranet.alxswe.com/rltoken/ssg5umgsMk5jKM8WRHk2Ug)
* [Base64 in Python](https://intranet.alxswe.com/rltoken/RpaPRyKx1rdHgRSUyuPfeg)
* [HTTP header Authorization](https://intranet.alxswe.com/rltoken/WlARq8tQPUGQq5VphLKM4w)
* [Flask](https://intranet.alxswe.com/rltoken/Zes_6jyFTaaem1lG47oTjQ)
* [Base64 - concept](https://intranet.alxswe.com/rltoken/br6Rp4iMaOce6EAC-JQnOw)
## Learning Objectives

### General

* What authentication means
* What Base64 is
* How to encode a string in Base64
* What Basic authentication means
* How to send the Authorization header

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
| 0. Simple-basic-API | [SOON](./) |
| 1. Error handler: Unauthorized | [api/v1/app.py](./api/v1/app.py), [api/v1/views/index.py](./api/v1/views/index.py) |
| 2. Error handler: Forbidden | [api/v1/app.py](./api/v1/app.py), [api/v1/views/index.py](./api/v1/views/index.py) |
| 3. Auth class | [api/v1/auth](./api/v1/auth), [api/v1/auth/__init__.py](./api/v1/auth/__init__.py), [api/v1/auth/auth.py](./api/v1/auth/auth.py) |
| 4. Define which routes don't need authentication | [api/v1/auth/auth.py](./api/v1/auth/auth.py) |
| 5. Request validation! | [api/v1/app.py](./api/v1/app.py), [api/v1/auth/auth.py](./api/v1/auth/auth.py) |
| 6. Basic auth | [api/v1/app.py](./api/v1/app.py), [api/v1/auth/basic_auth.py](./api/v1/auth/basic_auth.py) |
| 7. Basic - Base64 part | [api/v1/auth/basic_auth.py](./api/v1/auth/basic_auth.py) |
| 8. Basic - Base64 decode | [api/v1/auth/basic_auth.py](./api/v1/auth/basic_auth.py) |
| 9. Basic - User credentials | [api/v1/auth/basic_auth.py](./api/v1/auth/basic_auth.py) |
| 10. Basic - User object | [api/v1/auth/basic_auth.py](./api/v1/auth/basic_auth.py) |
| 11. Basic - Overload current_user - and BOOM! | [api/v1/auth/basic_auth.py](./api/v1/auth/basic_auth.py) |
| 12. Basic - Allow password with ":" | [api/v1/auth/basic_auth.py](./api/v1/auth/basic_auth.py) |
| 13. Require auth with stars | [api/v1/auth/auth.py](./api/v1/auth/auth.py) |

## Done by: Mekonen Abera

