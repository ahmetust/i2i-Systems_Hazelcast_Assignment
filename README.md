# Hazelcast Assignment

Simple project for learning Hazelcast IMDG basics. The project compare the insertion and selection speed of the Hazelcast with Oracle database on Java project. 

20000 and 100000 random numbers are generated. They inserted in the Hazelcast and OracleSQL.

Insertion and Selection times are calculated and recorded in the table for both utilities.

### Hazelcast Insert and Select time for 20000 numbers
![Hazelcast20k](https://github.com/ahmetust/i2i-Systems_Hazelcast_Assignment/blob/main/Screenshots/Hazelcast20k.JPG)

### OracleSQL Insert and Select time for 20000 numbers
![OracleSQL20k](https://github.com/ahmetust/i2i-Systems_Hazelcast_Assignment/blob/main/Screenshots/oracle20k.JPG)

### Hazelcast Insert and Select time for 100000 numbers
![Hazelcast100k](https://github.com/ahmetust/i2i-Systems_Hazelcast_Assignment/blob/main/Screenshots/Hazelcast100k.JPG)

### OracleSQL Insert and Select time for 100000 numbers
![Hazelcast100k](https://github.com/ahmetust/i2i-Systems_Hazelcast_Assignment/blob/main/Screenshots/oracle100k.JPG)


| Data Amount   | Hazelcast Insert  | OracleSQL Insert | Hazelcast Select  | OracleSQL Select |
| ------------  | ----------------- | -----------------|-------------------|------------------|
| 20000         |      528 ms       |      5512 ms     |      327 ms       |       349 ms     |
| 100000        |     2358 ms       |     29853 ms     |     1581 ms       |      1634 ms     |
