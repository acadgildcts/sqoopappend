
[acadgild@localhost ~]$ sqoop import --connect jdbc:mysql://localhost/ecommerce --username root --password acadgild --table Orders --target-dir /ecommerce -m 1 --incremental append --check-column acc --last-value 15
check syntax alone
