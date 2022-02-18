# Unix-Cheat-Sheet

#### Copy file content to the clipboard  
on macOS ```pbcopy <file```  
on linux ```xsel <file```


#### Looping through content of a file in Bash
```bash
while read p; do
echo "$p"
done <file.txt
```
