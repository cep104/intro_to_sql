##INTRO TO SQL

DB Browser for SQLite is available here: https://sqlitebrowser.org/ 

##Table Commands

Create a table: 
-- CREATE TABLE dogs (id INTEGER PRIMARY KEY, name TEXT, age TEXT);```

SQLite accepts the following value types: Integer, real, text, blob, null.

Add a Column to a Table:

-- ALTER TABLE dogs ADD COLUMN temperment TEXT;

Delete a table:

DROP TABLE dogs;

###CRUD Commands 
CREATE 
READ 
UPDATE
DELETE

Create

  -- INSERT INTO [tableName] (attr1, attr2) VALUES (value1, value2);
  INSERT INTO states (name, population) VALUES (“New York”, 19);
Never add an ID when inserting!

Read

--  SELECT [what we want to select] FROM [tableName] WHERE attr [conditional] "attr_value";
SELECT * FROM states WHERE name = "New York";

Update

  -- UPDATE [tableName] SET [columnName] = [new value] WHERE [columnName] = [value];
  UPDATE states SET population = 20 WHERE name = “New York”;

Delete

  -- DELETE FROM [tableName] WHERE [columnName] = [value];
  DELETE FROM states WHERE name = “New York”;







