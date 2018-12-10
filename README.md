# cmsms_vul
## XSS-1
When modifying the email, if the format is wrong, the response contains the previously entered email value. At this time, the XSS vulnerability will be started.   
![change password](1.png "") 
![change password](2.png "") 

## XSS-2
When creating Shortcuts, the system does not detect the Title, which will cause a storage XSS vulnerability. 
![change password](3.png "") 
The value of inputting is 
```
"></script><script>alert(11)</script>
```
![change password](4.png "")
