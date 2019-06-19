# Watcher-Engine
- Watcher Engine
	- Features
		* Completely DB Agnostic
	- Under the hood
		- Relational DB
			- DB1 Item
			- Relationship with DB2
		- DB 1 - ONE WAY CONNECTION
			- Must Exist when creating a new watcher db
		- DB2 can be built via Watcher
	- 1. Watcher Looking for Changes on DB1
	- 2. Send Notification to user of all changes in Data DB1 has been changed
		- Can Watch Only Specific Keys
		- Reports Can be Generated
		- Changes can be ignored
	- 3. Watcher Looks for Changes in DB2
		- Changes can be generated via Watcher Engine

