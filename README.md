# Sources for my DHBW lectures
## Prerequisites
Python must be installed.

Create Python virtual environments to separate different projects, e.g. with [uv](https://docs.astral.sh/uv/) First create the virtual environment, then activate it and finally install the packages:
```
uv venv
.venv\Scripts\activate
uv pip install -r requirements.txt
```

Create a .env file with entries:
```
OPENAI_API_KEY=
DB_HOST=
DB_NAME=
DB_USER=
DB_PASSWORD=
```

Start of jupyter lab with uv:
```
uv run --with jupyter jupyter lab
```
