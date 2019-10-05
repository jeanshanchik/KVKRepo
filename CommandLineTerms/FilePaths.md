## File Paths in linux

### What is it?
A path is the specifying location of a file or a directory from the root directory. 
### Why do you do it?
A file path would be useful for someone to identify where in the file system they are. Their location could be deep in multiple directories and finding an exact location can get tedious.
### How do you do it?
File Paths have several "**/**" in them depending on where in the directory you are. To write a file path of a directory, a slash (/) is the separator between them. 

![Directory Location](https://github.com/enforcer20/KVKRepo/blob/master/VI_image/Directory_location.png)

The above image's path would be the following: **/Users/karanwalanj/desktop/kvkrepo**

The file's location must be determined with respect to root. When you have more than one "**/**" in a path name, for each such "**/**", you have to descend one level in the file system like the directory, *kvkrepo* is one level below *karanwalanj* and two levels below the root directory (Macintosh HD in this example).


### Sources

1. [Source #1](https://www.geeksforgeeks.org/absolute-relative-pathnames-unix/)
