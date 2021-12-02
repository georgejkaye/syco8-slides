# New latex document

This repo has been created from the 'latex-template' repo.

This project uses *submodules* to share diagrams and things between repos. 
To make sure you have them all pulled, do this to initialise them:

```sh
git submodule update --init
```

Occasionally you might want to do this to update the submodules:

```sh
git submodule foreach git pull origin main
```
