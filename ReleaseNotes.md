### New in 1.6.0
* Creating and restoring BACPAC files

### New in 1.5.0
* `RestoreSqlBackup` provides ability to restore database backups from `.bak` files

### New in 1.4.0
* `SetSqlCommandTimeout` provides ability to set default timeout for all SQL operations


### New in 1.3.0 
* `OpenSqlConnection` provides an open connection to the database - for re-using in multiple commands execution.
* Overrides for `ExecuteSqlCommand` and `ExecuteSqlFile` to take `SqlConnection` object instaed of connection string.

### New in 1.2.1
* Alias to CreateDatabase - fails if the database already exists.

### New in 1.1.1 (Released 2016/10/20)
* Functionality to work with LocalDB instances.

### New in 1.0.1 (Released 2016/09/08)
* Initial methods for `DropDatabase`, `CreateDatabaseIfNotExists`, `DropAndCreateDatabase`, `ExecuteSqlCommand`, `ExecuteSqlFile`.

