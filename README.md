JsonDB is a pure java database that stores its data as Json Files.

A very small memory footprint, runs embedded within your java program.

Provides APIs that are very similar and inspired by MongoDB.

Provides a Apache JxPath based query system.

Visit http://jsondb.io for detailed information about Jsondb, Why Jsondb and Using Jsondb


A Jsondb data file in its entirety is not a valid JSON string, hence you cannot edit the complete Jsondb data file in a standard JSON conscious text editor. This makes it difficult to manully edit the file if the schema is complex.

However each row in a Jsondb data file (upto the LF) is expected to be a valid JSON document. This plugin when installed along with the Atom Editor can help to manually edit a Jsondb data file.

Note: MongoDB import files have a similar problem with manual editing, this plugin can be used for those files or any similar files

