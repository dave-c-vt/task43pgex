# task43pgex

for viewing Task 43 data model in PG Admin

## install

``` bash
docker-compose up -d
```

## connect

 http://localhost:5050/
 u: admin@admin.com
 p: root

## configure

1. connect as in above
1. click `Add New Server`
    1. Name: task43ex
    1. Connection: [your-LAN-IP-address]
    1. Username: root
    1. Password: root
1. in the left pane, navigate to task43ex > Databases > test_db > Schemas > public
1. right click on public and click `CREATE Script`
1. delete what's in the Query Editor, paste in the `task43_postgre.sql` script and run with play button
1. clear again, paste in the contents of the `iea43_wra_data_model_demo_data.sql` file, and run again
1 in the left pane, right-click `test_db` and choose `Generate ERD`



## reference

https://github.com/IEA-Task-43/digital_wra_data_standard


