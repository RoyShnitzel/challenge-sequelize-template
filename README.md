# Challenge-Sequelize

## Description

I11n this challenge we will be building basic ORM functionallity base on Sequelize usin mysql2

--- 

## Main Goal

Implementing the next functions: 

* Insert ()

* BulkInsert ()

* FindAll ()

* FindOne ()

* FindByPk ()

* Update ()

* soft/hard Destroy ()

* Restore ()

---
 
## First Steps

1. Clone template repository

2. Run ``` $npm i ```

3. If you want to run the tests locally, connect to your MySql in the [test connection statment](./test.test.js), which is located in the ``` beforeAll() ``` in the main test.

![sql connection](./ReadMePics/SQLconnection.png)

--- 

## Starting The Challenge

### If you are not famillier with Sequelize syntax:

#### Insert 
``` Model.Insert({... the object containing the value you want to insert}) ```
* [sequelize create reference](https://sequelize.org/master/manual/model-querying-basics.html#simple-insert-queries)
  ##### Related Queries
  * [SQL INSERT Query Reference](https://www.w3schools.com/sql/sql_insert.asp/)

#### Bulk Insert
``` Model.BulkInsert([... array with the objects  you want to insert]) ```
* [sequelize bulk create reference](https://sequelize.org/master/manual/model-querying-basics.html#creating-in-bulk)
  ##### Related Queries
  * [SQL INSERT Query Reference](https://www.w3schools.com/sql/sql_insert.asp/)


#### FindAll 
``` Model.findAll({ ```
     ```... the object containing the select query condition you want to apply}) ```
* [sequelize findAll reference](https://sequelize.org/master/manual/model-querying-basics.html#simple-select-queries)
  ##### Related Queries
  * [SQL SELECT Statement Reference](https://www.w3schools.com/sql/sql_select.asp)
  * [SQL WHERE](https://www.w3schools.com/sql/sql_where.asp/)
  * [SQL ORDER BY](https://www.w3schools.com/sql/sql_orderby.asp/)
  * [SQL LIMIT](https://www.w3schools.com/sql/sql_top.asp/)

#### FindOne
``` Model.FindOne({... the object containing the select query condition you want to apply}) ```
* [sequelize findOne reference](https://sequelize.org/master/manual/model-querying-finders.html#-code-findone--code-)
  ##### Related Queries
  * [SQL SELECT Statement Reference](https://www.w3schools.com/sql/sql_select.asp)
  * [SQL WHERE](https://www.w3schools.com/sql/sql_where.asp/)
  * [SQL ORDER BY](https://www.w3schools.com/sql/sql_orderby.asp/)
  * [SQL LIMIT](https://www.w3schools.com/sql/sql_top.asp/)

#### FindByPK
``` Model.FindByPk(Priority Key) ```
* [sequelize findByPk reference](https://sequelize.org/master/manual/model-querying-finders.html#-code-findbypk--code-)
  ##### Related Queries
  * [SQL SELECT Statement Reference](https://www.w3schools.com/sql/sql_select.asp)
  * [SQL WHERE](https://www.w3schools.com/sql/sql_where.asp/)

#### Update
``` Model.Update({... the object containing the where condition, that you want to update}) ```
* [sequelize updete reference](https://sequelize.org/master/manual/model-querying-basics.html#simple-update-queries)
  ##### Related Queries
  * [SQL UPDATE](https://www.w3schools.com/sql/sql_update.asp)

#### Soft/Hard Destroy 
``` Model.Destroy ({... the object containing the conditions for the rows that you want to delete, to hard delete add force:true}) ```
* [sequelize destroy reference](https://sequelize.org/master/manual/model-querying-basics.html#simple-delete-queries)
* [sequelize paranoid reference](https://sequelize.org/master/manual/paranoid.html)
  ##### Related Queries
  * [SQL DELETE](https://www.w3schools.com/sql/sql_delete.asp)
  * [SQL UPDATE](https://www.w3schools.com/sql/sql_update.asp)

#### Restore
``` Model.Restore ({... the object containing the conditions for the rows that you want to restore}, without object restor all) ``` 
* [sequelize restor reference](https://sequelize.org/master/manual/paranoid.html#restoring)
* [sequelize paranoid reference](https://sequelize.org/master/manual/paranoid.html)
  ##### Related Queries
  * [SQL UPDATE](https://www.w3schools.com/sql/sql_update.asp)


---

## Submiting The Challenge

---

## Usefull Links
* [SQL Keywords Reference](https://www.w3schools.com/sql/sql_ref_keywords.asp)
* [SQL Queries Reference](https://www.w3schools.com/sql/sql_quickref.asp)







