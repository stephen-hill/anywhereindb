# How It Works #
## Basic Idea ##
This project is based on basic **SQL** query.
Let me share my algorithm of this project.


### Steps ###
  1. Find the list of table in the database
  1. For all fields add it in the search\_SQL Query
  1. run the Search\_SQL



### Algorithm ###
```
   all_table_array = "SHOW TABLES"; 

   for(i=0; i < sizeof(all_table_array); ++i)
   {

     fields_in_this_table = "desc ". all_table_array[i];



     search_Sql = 'select * from all_table_array[i] where '
     for(j=0;j < sizeof(fields_in_this_table);++j)
     {
       
          search_Sql +=   fields_in_this_table[j] + "like %" + search_text + "%"; 


       
     }
    
      // Run the search_Sql
      // Show the Result 


   }
     



```

## SQL Query ##
  1. ` show tables `
  1. ` desc table1 `
  1. ` Select * from table1 where varchar1 like %search_text% or varchar2 like %search_text% or text1 like %search_text% `
