# pyChangeFilenameByUsingParentDirectoryName

The directory structure and file names of a path are below before changing the file names.
~~~
+---112
|   +---3000
|   |       001.jpeg
|   |       002.jpeg
|   |       003.jpeg
|   |       004.jpeg
|   |       005.jpeg
|   |       
|   +---3001
|   |       000.jpeg
|   |       001.jpeg
|   |       002.jpeg
|   |       003.jpeg
|   |       005.jpeg
|   |       
|   +---3003
|   |       000.jpeg
|   |       001.jpeg
|   |       002.jpeg
|   |       004.jpeg
|   |       005.jpeg

~~~

After changing the file names, the directory structure and file names will be below.
~~~
+---112
|       1123000001.jpeg
|       1123000002.jpeg
|       1123000003.jpeg
|       1123000004.jpeg
|       1123000005.jpeg
|       1123001001.jpeg
|       1123001002.jpeg
|       1123001003.jpeg
|       1123001004.jpeg
|       1123001005.jpeg
|       1123003001.jpeg
|       1123003002.jpeg
|       1123003003.jpeg
|       1123003004.jpeg
|       1123003005.jpeg
~~~
