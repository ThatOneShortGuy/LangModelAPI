# How to Use
1. Add this repository as a submodule to your project.
```bash
git submodule add https://github.com/ThatOneShortGuy/LangModelAPI.git
```
2. Use the following code to import the module and use it in your project.
```python
from LangModelAPI import start_server, get_model_info

start_server()
print(get_model_info())
```