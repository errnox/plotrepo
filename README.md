# Plotrepo

```
./plotrepo /path/to/repository | dot -Tpng > output.png
```

`plotrepo` gives a quick-and-dirty visual overview of a `git` repository's history.
 
This depends on the `grit` gem and requires Graphviz to be available.

**Caution:** It breaks if there are `Digraph` syntax-like elements in the repository's history. No escaping or sanitization is done whatsoever.

![Output Screenshot](res/output.png)
