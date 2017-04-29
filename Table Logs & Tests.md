# Data Examples

**Binding Pattern Cards**
  * Data to be ingested
    1. ID number
    2. Call number
    3. Title
    4. Color
    5. Type
    6. Machine Sew Thru Fold

![bpcs](/media/example_BPCs.jpg)

## Tip #1

> ![format](/media/format_output.png)

[source](https://www.tutorialspoint.com/sqlite/sqlite_commands.htm)

### My first table attempt 
- following steps from the tutorial returned the dreaded *command not found* 
- after searching [stack overflow](http://stackoverflow.com/questions/2771001/create-sqlite3-database-at-prompt), I tried with success an alternate method of creation
```
.open BPCTable.db
```

- below is my first write up of my table creation query. i find color coding helpful to make sure all parts are included
> ![test_table](/media/test_table.jpeg)

- unfortunatley it was not sucessful
> ![error](/media/table_creation_error.png)

- even though my test was unsuccessful, i went ahead and created an example of how I'd create my actual BPC table 
> ![BPC_table_ex](/media/practice_BPC_table.jpeg)
