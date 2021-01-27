# Shell Data Processing 

## Important Powershell commands
- See Your Current Directory
```
pwd
```
- Change Current Directory
```
cd
cd..
```
- See Files/Directories In Current Directory
```
ls
```
- Curl Command
```
curl "http://shakespeare.mit.edu/romeo_juliet/full.html" -O "data.txt"
```
- Command to Find Most Common Words
```
$  tr ' ' '\12' < data.txt | sort | uniq -c | sort -nr > result.txt
```
    