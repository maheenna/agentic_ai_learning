## 🚀 Creating a New Project with uv

You can quickly create a new Python project using `uv` with the following command:

```powershell
uv init --package project_1
```
This will create a new folder named project_1 with a basic project structure and a pyproject.toml file.

## 🧭 Navigate into the project
```bash
cd project_1
```
💻 Open the project in VS Code
```powershell
code .
```
Make sure you have the VS Code CLI installed for the code command to work.

## ⚙️ Add a Custom Command
You can define custom commands inside your pyproject.toml file under the 
[project.scripts] section.

For example:

[project.scripts]

hello_1 = "project_1.hello:hello"

Now you can run your script using:

```powershell
uv run hello_1
```
This is a handy way to define and run project-specific commands easily