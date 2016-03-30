# luasql
mysql and sqlite3 module for NPL runtime

## How to Install
Download and install here
[[https://github.com/LiXizhi/luasql/releases/tag/v1.0]]

### How to Use 
Once you have installed those dlls, you can use it like below 
```lua
NPL.load("(gl)script/ide/mysql/mysql.lua");
local MySql = commonlib.gettable("System.Database.MySql");
local mysql_db = MySql:new():init(db_user, db_password, db_name, db_host, db_port);
```
