treedir
======

A tool to tree a directory like tree in Windows Dos

Install
-------
* `npm install treedir -g`


Usage
-----
* `dtree -f`

  tree all the files and directory in recursion

* `dtree -l 1`

  tree the directory just 1 hierarchy. 1 could be other integer such as 2,3,4...

Example
----
`dtree -l 1`
└─treedir
   ├─.git
   ├─.gitignore
   ├─.npmignore
   ├─README.md
   ├─bin
   ├─node_modules
   ├─package.json
   └─tree.js