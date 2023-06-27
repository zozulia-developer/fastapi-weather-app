FastAPI Weather App
===

Overview
===
API Application for getting weather info using [openweathermap](https://openweathermap.org/).

Installation and startup
===
- ### Install virtual environment
```commandline
    virtualenv -p /usr/bin/python2.11 <env_name>
```

- ### Activate virtual environment
```commandline
    source <env_name>/bin/activate
```

- ### Install requirements
```commandline
    pip install -r requirements.txt
```

- ### Run application
```commandline
    python main.py
```

Tech Stack
===
`Python version: 3.11`
- **FastApi**
- **pydantic**
- **aiofiles**
- **httpx**
- **Jinja2**
- **starlette**