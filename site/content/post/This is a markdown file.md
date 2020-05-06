# This is the api plan




Dreamfactory API
Loopback
Express.js gateway
TyK
KONG API
FUSIO project
RedHat api opensource
Feathers.js
Nest.js



https://afterlogic.com/webmail-client
https://www.horde.org/apps/webmail
https://roundcube.net/
https://github.com/cozy-labs/emails


https://bhi.ma/screenshots.html

Fhirbase fhir api 
Fhir Hapi api
Asymitrik fhir api





Database based on postgreSQL

1. PostgreSQL
2. Postgres-XL
3. Greenplum
4. Citus
5. enterprizeDB
6. YugabyteDB
7. Crate DB
8. ToroDB
9. AgensGraph
10. 

https://wiki.postgresql.org/wiki/PostgreSQL_derived_databases


monetDB
Clickhouse
Crate DB

https://github.com/PostgREST/postgrest

https://www.percona.com/software

Postgres to clickhouse

## When to use ClickHouse

For analytics over stream of clean, well structured and immutable events or logs. It is recommended to put each such stream into a single wide fact table with pre-joined dimensions.

Some examples of viable applications:

Web and App analytics
Advertising networks and RTB
Telecommunications
E-commerce and finance
Information security
Monitoring and telemetry
Time series
Business intelligence
Online games
Internet of Things



## API Audit Log Options
The usage below defines rules about what the audit log should record and what data it should include:

PARAMETER	DESCRIPTION
AUDIT_LEVEL	0 - Disable audit log (default setting).
1 - Log event metadata.
2 - Log event metadata and request body.
3 - Log event metadata, request body, and response body. Each log transaction for a request/response pair uses the same auditID value.

See Audit Level Logging for a table that displays what each setting logs.
AUDIT_LOG_PATH	Log path for Rancher Server API. Default path is /var/log/auditlog/rancher-api-audit.log. You can mount the log directory to host. 

Usage Example: AUDIT_LOG_PATH=/my/custom/path/
AUDIT_LOG_MAXAGE	Defined the maximum number of days to retain old audit log files. Default is 10 days.
AUDIT_LOG_MAXBACKUP	Defines the maximum number of audit log files to retain. Default is 10.
AUDIT_LOG_MAXSIZE	Defines the maximum size in megabytes of the audit log file before it gets rotated. Default size is 100M.