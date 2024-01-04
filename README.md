# A shorn tutorial about git base  
---
## Making repository  
1. Make local repo  
```bash  
mkdir localrepo  
```  
2. Go inside it  
```bash
cd localrepo  
```  
3. Initial git repository  
```bash  
git init  
```  

## Making commit  
1. Add file with changes to index  
```bash  
git add filewithchanges.txt  
```  
2. Make commit  
```bash  
git commit -m "Commit description"
```  

## Add to remote repository on a GitHub  
1. Create repository on a GitHub  
2. Attache local with remote repository  
```bash  
git remote add origin https://github.com/youraccount/remoterepo.git  
```
3. Push your commits  
```bash  
git push -u origin main  
```
