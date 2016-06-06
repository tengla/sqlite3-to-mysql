
== sqlite3-to-mysql

Simple sed script for attempting to convert Sqlite3 sql
to MySql sql.

== Usage:

 sqlite3-to-mysql filename.sql > filename.new.sql

== Notes

Please note that sed needs to be in your $PATH

Not guaranteed to work, but can serve as a starting point.

Note that varchar will be translated to varchar(255).

Decided to make this after trying the yaml_db gem,
which I found to be excruciatingly slow for any dataset of considerable size.
