# Duplicate_Logs_Data


This is the repository containing the data for paper "Studying Duplicate Logging Statements and Their Relationships with Code Clones". 

- `LoggingStatement.zip` contains the logging statements with their related information extracted from the studied systems
  For each line of logging statement:
  - `logcall` represents for the logging library that a logging statement invokes
  - `parameter` lists all the parameters of this logging statement (including static message and dynamic variables)
  - `constant` shows the static message of a logging statement
  - `method` shows the verbosity level of this logging statement
  - `callsite` represents for the class and method of that this logging statement locates in
  - `line` shows the line number that this logging statement locates at
  - `superclass` shows the parent class or interface of the class that this logging statements locates in
- `DupLogs.zip` contains the lists of duplicate logging statements for each studied system
- `Instances.zip` contains the lists of duplicate logging code smells

