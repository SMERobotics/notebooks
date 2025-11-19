# notebooks
put ts math here

uv recommended, [install here](https://docs.astral.sh/uv/getting-started/installation)<br>
JupyterLab notebooks recommended, [install here](https://jupyter.org/install)

```bash
uv venv .venv

# windows users
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
.venv/Scripts/activate.ps1
# macos/unix users
.venv/Scripts/activate

uv pip install -r pyproject.toml

# windows users
.venv/Scripts/jython-run.exe
# macos/unix users
.venv/Scripts/jython-run
```