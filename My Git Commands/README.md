### Create Empty Branch
```cd MyCode``` #Navigate to Repository *MyCode*\
```git checkout --orphan test``` #Create Local Branch *test*\
```git rm -rf``` #Remove all files from this local branch
```git commit --allow-empty -m "Empty Branch Created"``` #Empty commit
```git push origin Working``` #Now push your Empty Branch to Origin
