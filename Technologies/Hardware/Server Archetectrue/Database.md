A database [[Server]] typically operates in tandem with another type of server. This kind of server simply exists to store data in groups of other database servers known as [[Data Center]].

There are countless methods of keeping data that operate on different theories. One of the more common types is known as “[[SQL]]” or “Structured Query Language”.

Database programmers can create databases on these servers using scripting in the language of the database.

Web applications usually have their server-side components connect to a Database server to grab data as users request it.
Note:
	A good practice is to have webservers and database servers on different machines. The reason that database servers should exist on their own is for security.

If a hacker gains access to the main webserver but not the database server, they will be able easily to retrieve or modify the data stored in the database server.

Some popular Database servers include
	MySQL, MariaDB, Microsoft SQL, Oracle Database.
