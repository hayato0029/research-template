# research-template

## Build Environment

1. install [uv](https://github.com/astral-sh/uv)

```bash
# On macOS and Linux.
$ curl -LsSf https://astral.sh/uv/install.sh | sh

# On Windows.
$ powershell -c "irm https://astral.sh/uv/install.ps1 | iex"

# With pip.
$ pip install uv
```

2. create virtual enviroment

```
uv sync
```

3. activate pre-commit

```
uv run pre-commit install
```

4. activate virtual enviroment
```
. .venv/bin/activate
```

5. deactivate virtual enviroment
```
deactivate
```

reference
- [uvだけでPythonプロジェクトを管理する](https://zenn.dev/turing_motors/articles/594fbef42a36ee)
