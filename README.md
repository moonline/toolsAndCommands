toolsAndCommands
================

Shortcuts and commands like \ch(for \chapter), \se(for \section), images, boxes, ... for efficient latex documents.


git usage help
---------------
http://chrisjean.com/2009/04/20/git-submodules-adding-using-removing-and-updating/

### Add Sobmodule:
- git submodule add {repoUrl}
- Example: git submodule add git@github.com:moonline/toolsAndCommands.git
  

### update submodule to bound version:
git submodule update

### update submodules to newest version:
git submodule foreach git pull

### remove submodule:
- Remove the submodule’s entry in the .gitmodules file.
- Remove the submodule’s entry in the .git/config.
- Run “git rm –cached {plugin path}“. 

