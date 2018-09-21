Titanium Hacks

https://medium.com/all-titanium/using-models-and-migrations-in-titanium-a03e3a6b0d6f
When you are modifying an existing table, you need to do the following:

Make sure your model reflects the final version of the table, including the fields you are adding.
Create an initial migration that uses the migrator.createTable to create your ORIGINAL database structure.
Create a second migration that does the add column sql code.
