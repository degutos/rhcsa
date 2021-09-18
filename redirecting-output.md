# Redirecting output

Redirect output to a file and error to another file
```
$ ls /var /jose > output.log 2> error.log
```

Redirect output and errors to the same file
```
$ ls /usr /zoe > output.log 2>&1
```

Redirect output and errors to the same file - another way
```
ls /usr /zoe &> output.log
```

Redirecting resolv.conf content to another command using PIPE
```
cat /etc/resolv.conf | wc -l
```

Show command output to screen and to a file 
```
$ ls -l /var | tee var-content.log
```

Show command output to screen and append content to a file 
```
$ ls -l /boot | tee -a var-content.log
```


