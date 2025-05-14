# txAdminRecipe
**Description:** A complete FiveM RP Server based on the vRP framework.

## Read Before Proceeding
You must create your database first! Follow the steps below for first time database setup process.
 
### Setting up your Database (Windows)
1.  Download/Install [**XAMPP**](https://www.apachefriends.org/download.html)
    -  Once installed, you will want to make xampp-control run as Admin
2.  Install MySQL service and click Start
    -  On the XAMPP Control Panel, click Config
    -  Click the X next to MySQL to install the service
3.  Open your DBMS (phpmyadmin or HeidiSQL)
    -  If using HeidiSQL, download from here [https://www.heidisql.com/download.php](https://www.heidisql.com/download.php)
4.  Create a new DB with the name **vRP**, username **vRP**, password **password**
    -  If you want to change your information, make sure to update the file vrp/cfg/base.lua lines 8-10.

### Setting your Database Connection String
1.  When prompted in txAdmin, use the following DB Connection string: `mysql://vRP:password@localhost/vRP?multipleStatements=true`
    - If you have changed your information after original setup, make sure to update the connection string accordingly - `mysql://username:password@localhost/db_name?multipleStatements=true`

If you have any issues or questions, join our [**discord server**](https://discord.gg/yFfj2pbe6d) and ask the community

This recipe runs inside [**txAdmin**](https://github.com/tabarra/txAdmin).
Please check the [**Recipe Documentation Page**](https://github.com/tabarra/txAdmin/blob/master/docs/recipe.md).
