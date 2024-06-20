# Cook

An utiltity for cooking recipes.

## Creating your own recipes using CK-edit

ckedit will create a new recipe or update an existing one.
In the most basic mode it will just open a file and allow me to select text ranges, give them a name. 
Then when you invoke the recipe `ck` will ask what value that range should be replaced by.

```shell
ckedit new-recipe-from-git <git-range>
```

This will create a recipe from a git commit.


```shell
ckedit new-recipe-from-files filename
```

This will create a new recipe from one or multiple files. If the path include subdirectories than the files will be created in sub-directories.

