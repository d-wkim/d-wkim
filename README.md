[![PythonAnywhere](https://img.shields.io/badge/PythonAnywhere-3776AB?logo=python&logoColor=fff)](https://www.pythonanywhere.com/user/dongwkim/)
[![Anaconda](https://img.shields.io/badge/Anaconda-44A833?logo=anaconda&logoColor=fff)](https://anaconda.com/app/)
[![JupyterLite](https://img.shields.io/badge/Jupyter-ffa500?logo=Jupyter&logoColor=fff)](https://dong-wkim.github.io/jupyterlite/lab/index.html)


```python
myst = f"""version: 1
project:
  id: 30084285-534d-4579-9ecf-b55598a951ab
  title: Dong Woon Kim
  github: https://github.com/d-wkim/d-wkim
  template: book-theme
  toc:
    - file: README.md
  # options:
  #   favicon: favicon.ico
  #   logo: site_logo.png
"""

with open(f"./myst.yml", "w") as f:
    f.write(myst)
```

```python
!git add -A
!git commit -m f""""Update"""
!git push --force
```

https://www.dongwkim.com

```python

```
