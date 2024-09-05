# Sara's ML Notebooks

- Link to published Jupyter notebooks: https://saralsy.github.io/data-science/

## Topics

-

Command to publish more notebooks:

```
poetry run jupyter-book build myfirstbook
git add -A
git commit -m "publish"
git push
poetry run ghp-import -n -p -f myfirstbook/_build/html
```
