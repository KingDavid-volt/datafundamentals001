# Migrate Azure Database for MySQL - Single Server to Flexible Server offline using DMS via the Azure portal
#### by Kingsley David
***
Outline
1. Download and install Mysql database server and Mysql workbench
1. create two databases on a Local Mysql server
2. ![create database](https://github.com/KingDavid-volt/datafundamentals001/blob/208361b0acb8dbcdb347ee7c10fea2698f9bc5bb/images/create%20database2.png)

4. Create a resource group on azure portal
5. ![create resource group](https://github.com/KingDavid-volt/datafundamentals001/blob/208361b0acb8dbcdb347ee7c10fea2698f9bc5bb/images/Create%20a%20resource%20group%20on%20azure.png)

7. create a azure Mysql single server 
8. ![create sql sever](https://github.com/KingDavid-volt/datafundamentals001/blob/208361b0acb8dbcdb347ee7c10fea2698f9bc5bb/images/Create%20Sql%20sever%20on%20azure.png)

5. create a azure Mysql flexible server
6. ![create flexible sever](https://github.com/KingDavid-volt/datafundamentals001/blob/38ad98518b6b0773324a432a528bd08beac1a283/images/create%20sql%20flexible%20sever.png)

8. create a virtual network
9. ![create virtual network](https://github.com/KingDavid-volt/datafundamentals001/blob/38ad98518b6b0773324a432a528bd08beac1a283/images/create%20virtual%20network.png)

11. create azure data migration service
12. ![create database migration service](https://github.com/KingDavid-volt/datafundamentals001/blob/805445ee13cb0ffac65df13e89dfff036fd90c5a/images/create%20databse%20migration%20service.png)

14. create a new migration
15. ![create data migration](https://github.com/KingDavid-volt/datafundamentals001/blob/38ad98518b6b0773324a432a528bd08beac1a283/images/create%20database%20migration.png)

17. move database 1 and 2 from local server to single server via manual export and import
18. ![export database](https://github.com/KingDavid-volt/datafundamentals001/blob/805445ee13cb0ffac65df13e89dfff036fd90c5a/images/export%20database.png)
19. ![import database](https://github.com/KingDavid-volt/datafundamentals001/blob/b5656485a1e68b88483eb7b0d4e1b1794a12d9ce/images/import%20database.png)

21. move database 1 from single server to flexible server via azure Data Migration Service
22. ![azure database migration](https://github.com/KingDavid-volt/datafundamentals001/blob/b5656485a1e68b88483eb7b0d4e1b1794a12d9ce/images/start%20migration.png)

1. Move database 2 from single server to flexible server via, Mysql workbench migration
2. ![workbench migration](https://github.com/KingDavid-volt/datafundamentals001/blob/b5656485a1e68b88483eb7b0d4e1b1794a12d9ce/images/mysql%20workbench%20migration.png)

***
[Download Mysql Server] (https://dev.mysql.com/downloads/installer/)

[Download Mysql Workbench] (https://dev.mysql.com/downloads/workbench/)

[SQL Sample Database Script] (https://www.sqltutorial.org/sql-sample-database/)

Resource created on Azure
![azure resources](https://github.com/KingDavid-volt/datafundamentals001/blob/94ec892b667feba94c69da172e7bec76d575548b/images/Azure%20resources.png)

Mysql workbench sever
![mysql workbench sever](https://github.com/KingDavid-volt/datafundamentals001/blob/94ec892b667feba94c69da172e7bec76d575548b/images/mysql%20workbench%20sever.png)
