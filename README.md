<p align="center">
  <a href="https://bhagavadgita.io">
    <img src="gita.png" alt="Bhagavad Gita" width="500">
  </a>
</p>

<p align="center">
  Backend code for BhagavadGita.io which is an built for Gita readers by Gita readers.
</p>

## Project Structure
```
.
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── README.md
├── app
│   ├── __init__.py
│   ├── main
│   │   └── __init__.py
│   ├── models
│   │   └── __init__.py
│   ├── schemas
│   │   └── __init__.py
│   └── utils.py
├── config.py
├── gita.png
├── manage.py
└── tests
    └── test_basics.py
```

## Developing Locally

1. Fork this repository and clone the forked repository.
2. Create and activate a Python 3 virtualenv.
3. Use `pip install -r requirements.txt` to install the requirements.
4. `python manage.py runserver` to start the server.
5. API can be accessed at `http://127.0.0.1:5000`.