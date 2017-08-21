# Preparation

* mkdocs tools

```
# pip install mkdocs
# pip install mkdocs-material 
```


# How to Update

```
# git clone https://github.com/SHIFT-ware/page.git
# git checkout master  
```

Edit mkdocs.yml or some files under docs directory, then 


```
# mkdocs build
# mkdocs gh-deploy
```

Finally, you need to push the master repository.

```
# git add .
# git commit -m "Update"
# git push -u origin master
```

