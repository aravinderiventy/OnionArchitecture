1. Make sure to update the database connection string in Program.cs from WebApi project. Ex: (Data Source=(localdb)\\MSSQLLocalDB)

2. open up the package manager console and select the Persistence project as the default project 
add-migration Initial
update-database
The above commands will created the db and tables into it.

Finally run the project and perform Post action to add a new product.