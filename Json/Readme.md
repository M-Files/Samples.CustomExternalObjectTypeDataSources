# Example JSON External Object Type Data Source

This sample reads data from a set of `.json` files and can be used to create `User`, `Post` and `Comment` objects within M-Files.

The solution contains four projects:

* `ExtOTDS.Json` - contains the implementation of the M-Files data source interfaces, split into separate partial files for create/read/update/delete optioerations.
* `JsonDataProvider` - a sample read/write data provider that handles interacting with the underlying `.json` files on disk.
* `JsonDataProvider.Tests` - unit tests for the data provider.
* `Setup` - a sample setup program that installs the DLLs and creates the required registry entries.