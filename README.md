# Preparation

* mkdocs tools

```
# pip install mkdocs
# pip install mkdocs-material 
```


# How to Update

```
# git clone https://github.com/SHIFT-ware/ja.git
# git checkout master  
```

Edit mkdocs.yml or some files under the docs directory, then 


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

# Ref

* http://www.mkdocs.org/
* http://squidfunk.github.io/mkdocs-material/

