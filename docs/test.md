# Cacti TEST
---
template: overrides/main.html
---

<img src="http://10.1.126.164/graph_image.php?action=view&local_graph_id=481&rra_id=5" alt="CUCC" />


# Creating your site

After you've [installed] Material for MkDocs, you can bootstrap your project 
documentation using the `mkdocs` executable. Go to the directory where you want
your project to be located and enter:

```
mkdocs new .
```

Alternatively, if you're running Material for MkDocs from within Docker, use:

=== "Unix, Powershell"

    ```
    docker run --rm -it -v ${PWD}:/docs squidfunk/mkdocs-material new .
    ```

=== "Windows"

    ```
    docker run --rm -it -v "%cd%":/docs squidfunk/mkdocs-material new .
    ```

This will create the following structure:

```
.
├─ docs/
│  └─ index.md
└─ mkdocs.yml
```

  [installed]: index.md
-----

test keyboard : {{打开...}} 菜单，或按((CTRL)) + ((Shift)) + ((N))创建文件夹。((CTRL)) + ((S)) 保存 [[保存]]
