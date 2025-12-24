Moving a file can do two things move or rename a file. Move unlike [[Copy]] does not retain the original copy so we can use:
```bash
mv ~/Desktop/file.txt ~/Desktop/new.txt
```
This just renames the file to new.txt.

Moving something without changing the name is also simple just don't change the name in the new path/
```bash
mv ~/Downloads/file.txt ~/Desktop/file.txt
```

You can also move and rename in one command 
```bash
mv ~/Downloads/file.txt ~/Desktop/new.txt
```

Moving a directory works the exact same way 
```bash
mv ~/Downloads/Directory ~/Desktop/Directory
```

The primary difference between [[Copy]] and move is that copy duplicates a file while move takes the original and moves it. 