# SQL Notes

- Find the MySQL server port

```sql
SHOW GLOBAL VARIABLES LIKE 'PORT'; 
```

## Basic Commands

- `CREATE`
```sql
CREATE TABLE MOVIES(
    title varchar(20) NOT NULL,
    rating int,
    totalGross int NOT NULL,
    director varchar(20) NOT NULL,
    PRIMARY KEY (title),
    FOREIGN KEY (rating)
)
```