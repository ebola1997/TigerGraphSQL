# TigerGraphSQL
Query for TigerGraph, GSQL Script

Scriptnya

Create Vertex & Edge (Table & Relasinya kalo di RDBMS)
Create mapping data (Mapping data csv atau json ke dalam vertex dan Edge) proses EDA
Create Loading Job (Load data yang sudah dimapping sesuai map) proses ETL


---- Scriptnya cuma script basic, script lainnya (pembuatanan data stream, mapping dengan function, loading data json) di private repo

---------####-----

Output Query 1 & 2
(Create vertex & Edge + Create Graph)

![image](https://user-images.githubusercontent.com/59966599/197401283-d66fb478-1dde-46f5-8935-de59fe773ad9.png)

Output Query 3 & 4
(CREATE SCHEMA_CHANGE JOB + RUN SCHEMA_CHANGE JOB)

![image](https://user-images.githubusercontent.com/59966599/197401764-9789e4fb-1cad-466e-a229-539781ec0595.png)

![image](https://user-images.githubusercontent.com/59966599/197401866-005cd945-410e-4317-94be-a7b2f72c19f1.png)

Perbedaan Pembuatan Vertex pada Graph Global dan Graph Local, Vertex & Edge yang dibuat pada Graph Local tidak dapat digunakan pada Graph Local lain
