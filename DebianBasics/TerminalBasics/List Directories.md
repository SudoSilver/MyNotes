List directories is the command:
```bash 
ls
```

Which is a very useful command since it lists files and directories.

---
ls by itself lists files and directories but for hidden files we need a different command (hidden files are commonly referred to as dotfiles because they are prefixed with a . ) 

```bash
ls -a
```
This time we follow ls with the -a flag so it lists every file hidden or not.

---
ls by itself lists files and directories in the directory you are currently in but if you want to list files inside of another directory without moving to it: 
```bash
ls Desktop
```
This way we list all files and directories inside of the directory we have provided the path to.

---
We can combine a path and the -a flag to list all files even hidden files in a directory:
```bash 
ls Desktop -a
```
This shows every file inside of Desktop as an example 

---
ls just like [[Change Directory|cd]] can take both a relative or an absolute path.