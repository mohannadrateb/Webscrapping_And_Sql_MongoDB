## Webscrapping and connecting to a Relational Database and Non-Relational Database 

### Webscrapping.ipynb File
1. In this file I scrap the website: datajob.io
2. I use the Beautifulsoup Library to extract the required info from the website
3. I get the names of the comapnies, job_names, jobs_desc, jobs_req_and info
4. I save the information in a dataframe and export it to a .csv file

### Webscrapping_data_to_sql.ipynb
1. I import the csv file to a dataframe
2. I use the sqlalchemy library to create a Sql engine
3. I run multiple queries and got the results 

### Webscrapping_data_to_mongodb.ipynb
1. I import the csv file to df and  connect to mongodb  
2. I Inserted the records in the remote database
3. I ran multiple queries. 





