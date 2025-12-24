A directory is the same as a folder in windows. It is really simple to make one we just run:

```bash
mkdir hello
```

We can also use an absolute path:
```bash
mkdir ~/hello
```
this creates a directory named hello inside of the home directory.

We can also create a directory and its parent directories if they don't exist 
```bash
mkdir -p /a/b
```
this creates *b* if *a* exists but will also create *a* if it does not exist then create *b* inside of it. 