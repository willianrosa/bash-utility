# bash-utility
list of commands that I use daily

create current's folder symbolic link:
```bash
ln -s $(pwd) /opt/newlink
```

find in files:
```bash
find -name '*.sql' | xargs grep -ins --color mytext
```

 rename specific files recursivily
 ```bash
for i in $(find . -name '*.imported'); do mv $i ${i/.imported/}; done; 
 ```

pretty csv
```bash
cat data.csv | column -t -s, | less -S
```
