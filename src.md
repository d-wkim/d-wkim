[![PythonAnywhere](https://img.shields.io/badge/PythonAnywhere-3776AB?logo=python&logoColor=fff)](https://www.pythonanywhere.com/user/dongwkim/)
[![Anaconda](https://img.shields.io/badge/Anaconda-44A833?logo=anaconda&logoColor=fff)](https://anaconda.com/app/)
[![JupyterLite](https://img.shields.io/badge/Jupyter-ffa500?logo=Jupyter&logoColor=fff)](https://dong-wkim.github.io/jupyterlite/lab/index.html)


```python
myst = f"""# See docs at: https://mystmd.org/guide/frontmatter
version: 1
project:
  id: 40871a0f-221a-426f-9254-397b878c8e84
  # title: Dong Woon Kim, M.D.
  # description:
  # keywords: []
  # authors: []
  toc:
    - file: README.md
site:
  template: book-theme
  # options:
  #   favicon: favicon.ico
  #   logo: site_logo.png
"""

with open(f"./myst.yml", "w") as f:
    f.write(myst)
```
