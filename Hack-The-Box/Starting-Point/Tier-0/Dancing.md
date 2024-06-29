# Dancing

## Answers to questions

Task 1) What does the 3-letter acronym SMB stand for?

```text
server message block
```

Task 2) What port does SMB use to operate at?

```text
445
```

Task 3) What is the service name for port 445 that came up in our Nmap scan?

```text
microsoft-ds
```

![nmap.png](../../../../../_resources/nmap.png)


Task 4) What is the 'flag' or 'switch' that we can use with the smbclient utility to 'list' the available shares on Dancing?

```text
-L
```


![man-smbclient.png](../../../../../_resources/man-smbclient.png)


Task 5) How many shares are there on Dancing?

```text
4
```


![list-shares.png](../../../../../_resources/list-shares.png)

Task 6) What is the name of the share we are able to access in the end with a blank password?

```text
workshares
```

Task 7) What is the command we can use within the SMB shell to download the files we find?

```text
get
```

## Flag

![get-flag.png](../../../../../_resources/get-flag.png)