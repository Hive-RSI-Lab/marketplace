# Hive marketplace

The index of public modules for a Hive. `modules.json` is the list: name -> `repo`, `about`, optional `needs` and `recommended`. A Hive reads the same shape from its own `modules.json` and installs with `h2 module add NAME` (or `h2 module add <git URL>`).

Add or update a module: open a PR here changing its entry. Modules run with the Hive's rights and nobody reads them for you, so read a module before you add it. Other indexes (your own, a friend's) work the same way: any repo with this file.
