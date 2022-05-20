# ScssToCssCoverter

$ node-sass input.scss output.css compiles a single file manually.
$ node-sass input/ -o output/ compiles all the files in a folder manually.
$ node-sass -w input/ -o output/ compiles all the files in a folder automatically whenever the source file(s) are modified. -w adds a watch for changes to the file(s).