### Helpful Hive SQL Commands + Examples
`GRANT SELECT ON TABLE {table} TO USER {user};

alter table {original table name} rename to {new table name};

describe {table_name};'

show partitions {table_name}

ALTER TABLE {table name} DROP IF EXISTS PARTITION(date_generated >= "2024-05-18");

LATERAL VIEW EXPLODE
select {columns} from {table} lateral view explode({column with struc}) object_name as {give name} where {filter query};`