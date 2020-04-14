<p align="center">
  <a href="https://bhagavadgita.io">
    <img src="gita.png" alt="Logo" width="300">
  </a>

  <h3 align="center">BhagavadGita.io Backend</h3>

  <p align="center">
    Backend code for BhagavadGita.io v2, which is an app built for Gita readers by Gita readers.
    <br />
    <br />
    <a href="https://bhagavadgita.dev">View Demo</a>
    ·
    <a href="https://github.com/gita/bhagavad-gita-frontend/issues">Report Bug</a>
    ·
    <a href="https://github.com/gita/bhagavad-gita-frontend/issues">Request Feature</a>
  </p>
</p>

<p align="center">
  <a href="https://github.com/gita/bhagavad-gita-backend/blob/master/LICENSE">
    <img alt="LICENSE" src="https://img.shields.io/badge/License-GPLv3-blue.svg?maxAge=43200">
  </a>
  <a href="https://github.com/gita/bhagavad-gita-backend/actions?query=workflow%3ADev">
    <img alt="GitHub Actions" src="https://github.com/gita/bhagavad-gita-backend/workflows/Dev/badge.svg">
  </a>
  <a href="https://codecov.io/github/gita/bhagavad-gita-backend"><img alt="Coverage Status" src="https://img.shields.io/codecov/c/github/gita/bhagavad-gita-backend/master.svg?logo=codecov"></a>
  <a href="https://starcharts.herokuapp.com/gita/bhagavad-gita-backend"><img alt="Stars" src="https://img.shields.io/github/stars/gita/bhagavad-gita-backend.svg?style=social"></a>
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
