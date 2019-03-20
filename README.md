# Data migration with Maven and H2

This application allows the integration between Flyway and H2.

In this sample application we use the following topics:

* SpringBoot
* H2
* SQL
* Maven

## Flyway command line

Flyway Info

Prints the details and status information about all the migrations.

	mvn flyway:info

Flyway Migrate

Migrates the schema to the latest version. Flyway will create the schema history table automatically if it doesn’t exist:

	mvn flyway:migrate
	

Flyway Repair

Repairs the schema history table:

	mvn flyway:repair
	

Flyway Clean

Drops all objects (tables, views, procedures, triggers, …) in the configured schemas.:

	mvn flyway:clean
	
source: https://flywaydb.org/documentation/command/repair
