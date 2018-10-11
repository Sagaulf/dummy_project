Notes for myself to get better at structuring my python projects.

Project structure example (by kennethreitz): https://github.com/kennethreitz/samplemod

```
README.rst
LICENSE
setup.py
requirements.txt
sample/__init__.py
sample/core.py
sample/helpers.py
docs/conf.py
docs/index.rst
tests/test_basic.py
tests/test_advanced.py
```

Cheat sheet for markdown (make prettier readmes): https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
(Alternatively github documentation is here: https://help.github.com/articles/basic-writing-and-formatting-syntax/)

## Remember to:
1. Start using licences (don't be a noob): https://choosealicense.com/

2. Automate requirements.txt creation
   - Either create a python env and use *pip freeze/conda list > requirements.txt*
   - ... or use the module [´<pipreqs>](https://github.com/bndr/pipreqs) to generate from imports
3. Start including blueprints for development environment setup in setup.py
