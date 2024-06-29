# Information Gathering

Technologies : Spring, Java, Nginx

Non-standard URLs : 

```text
- img                     [Status: 200, Size: 0, Words: 1, Lines: 1, Duration: 357ms]
- login                   [Status: 405, Size: 226, Words: 7, Lines: 1, Duration: 195ms]
- info                    [Status: 200, Size: 2, Words: 1, Lines: 1, Duration: 717ms]
- health                  [Status: 200, Size: 104, Words: 1, Lines: 1, Duration: 473ms]
- trace                   [Status: 200, Size: 29749, Words: 401, Lines: 1, Duration: 404ms]
- error                   [Status: 500, Size: 88, Words: 3, Lines: 1, Duration: 400ms]
- metrics                 [Status: 200, Size: 1059, Words: 1, Lines: 1, Duration: 841ms]
- dump                    [Status: 200, Size: 273428, Words: 3, Lines: 1, Duration: 2585ms]
- env                     [Status: 200, Size: 3461, Words: 22, Lines: 1, Duration: 2830ms]

Spring boot actuator endpoints is activated ! 

"Spring Boot includes a number of additional features to help you monitor and manage your application when you push it to production."
```

# Exploit

I looked up the meaning of endpoints with Google, and found this : https://www.tchap.fr/la-pile-stack-et-le-tas-heap/

Look in "47. Endpoints > heapdump" here : https://repository.root-me.org/Exploitation%20-%20Web/EN%20-%20Spring%20boot%20-%20Reference%20guide.pdf



![heapdump.png](../../../../_resources/heapdump.png)


![heapdump-download.png](../../../../_resources/heapdump-download.png)


Look inside the heapdump (VisualVM) : 


![gzip.png](../../../../_resources/gzip.png)


![flag (3).png](../../../../_resources/flag%20%283%29.png)
