
## Step 05 - Create a .devcontainer Directory

- Create a .devcontainer directory with a devcontainer.json file for the development container setup:

```bash
.devcontainer (Folder)
├── devcontainer.json (File)
```
- Inside the .devcontainer folder, create devcontainer.json:
```bash
{
  "name": "Jupyter Notebook Dev Container",
  "image": "python:3.9",
  "extensions": ["ms-python.python"],
  "postCreateCommand": "pip install notebook",
  "forwardPorts": [8888],
  "remoteUser": "root"
}
```