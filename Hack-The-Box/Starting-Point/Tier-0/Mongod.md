# Mongod

## Answers to questions

Task1) How many TCP ports are open on the machine? 

```
2
```

![nmap (2).png](../../../../../_resources/nmap%20%282%29.png)

Task2) Which service is running on port 27017 of the remote host? 

 ```
Mongodb 3.6.8
```

Task3)  What type of database is MongoDB? (Choose: SQL or NoSQL) 

```
NoSQL
```

Task4)  What is the command name for the Mongo shell that is installed with the mongodb-clients package? 

```
mongo
```

![mongodb-clients.png](../../../../../_resources/mongodb-clients.png)

Task5) What is the command used for listing all the databases present on the MongoDB server? (No need to include a trailing ;) 

```
show dbs
```


![mongodb-connect.png](../../../../../_resources/mongodb-connect.png)


![show-dbs.png](../../../../../_resources/show-dbs.png)



Task6) What is the command used for listing out the collections in a database? (No need to include a trailing ;) 


```
show collections
```


![show-collections.png](../../../../../_resources/show-collections.png)


## Flag

Task7)  What is the command used for dumping the content of all the documents within the collection named flag in a format that is easy to read? 

```
db.flag.find().pretty()
```


![db-flag.png](../../../../../_resources/db-flag.png)

