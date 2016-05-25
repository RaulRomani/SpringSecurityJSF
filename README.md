# Spring security with JSF

This project show hot to make spring security works with JSF and just with one single table (check brach single-table)

```sql
CREATE TABLE `usuario` (
  `username` varchar(255) NOT NULL,
  `password` char(128) DEFAULT NULL,
  `authority` varchar(50) NOT NULL DEFAULT 'ROLE_SALER',
  `enabled` tinyint(1) DEFAULT '0',
  PRIMARY KEY (`username`)
) ENGINE=InnoDB DEFAULT CHARSET=utf8;
```




Source:
https://www.youtube.com/watch?v=DCd2O0At_fA