
```
# check all using port 
lsof -i
#or
netstat -tanp

# check target port
lsof -i:80

# check process detail (bin, args)
ps aux | grep <target process>
```
