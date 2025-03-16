## PS (Process Status)
used to display all the running process in the linux system.  

```ps``` = show the process of current shell  
PID - unique process ID
TTY - Terminal type of user logged in to  
TIME - amount of CPU in min and sec that process has been running  
CMD - name of the command that launched the progran.  

- __To see the running processes__  
```ps -e```  
```ps -a```  
```ps -ef| ef``` for full format

To see all running process in BSD (Berkeley Software Distribution) format.  
Ideally it gives you more information.  
```ps aux```  
```ps -ef | grep httpd```  

To see the process by username  
```ps -u root```  
```ps -G kali```  

To see the process tree  
```ps -ejH```  
```ps -ejH | grep httpd```

