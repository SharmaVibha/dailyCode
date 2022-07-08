**OPTIONS** 

1.  July 8, 2022
    
    **PURGE option with DROP TABLE statement -**
    
    The PURGE option will purge the table and its dependent objects so that they do not appear in the recycle bin. The risk of specifying the PURGE option is that you will not be able to recover the table. 
    ```
    DROP TABLE IF EXISTS test PURGE;
    ```
2. 
