# AutoDeleteScript
bash Script For Deleting Specific files

Here Bash Script Command i used:

```
#!/bin/bash
for X in *.png; do
    if [ "$X" != "filename.png" ]; then
        rm "$X"
    fi
done
```
write this Command in a file and save it with as .SH file and get premision to file as executable file.

for example 

autodelete.sh

