# Percona Distribution for PostgreSQL 14 Documentation

Percona Distribution for PostgreSQL is a collection of tools to assist you in managing your PostgreSQL
database system: it installs PostgreSQL and complements it by a selection of
extensions that enable solving essential practical tasks efficiently:


* [pg_repack](https://github.com/reorg/pg_repack) rebuilds
PostgreSQL database objects


* [pgAudit](https://www.pgaudit.org/) provides detailed session or object
audit logging via the standard PostgreSQL logging facility

* [pgAudit set_user](https://github.com/pgaudit/set_user) - The `set_user` part of `pgAudit` extension provides an additional layer of logging and control when unprivileged users must escalate themselves to superuser or object owner roles in order to perform needed maintenance tasks.

* [pgBackRest](https://pgbackrest.org/) is a backup and restore solution for
PostgreSQL


* [Patroni](https://patroni.readthedocs.io/en/latest/) is an HA (High Availability) solution for PostgreSQL.


* [pg_stat_monitor](https://github.com/percona/pg_stat_monitor) collects and aggregates statistics for PostgreSQL and provides histogram information.

* [PgBouncer](https://www.pgbouncer.org/) - a lightweight connection pooler for PostgreSQL
 

* [pgBadger](https://github.com/darold/pgbadger) - a fast PostgreSQL Log Analyzer.


* [wal2json](https://github.com/eulerto/wal2json) - a PostgreSQL logical decoding JSON output plugin.

* [HAProxy](http://www.haproxy.org/) - a high-availability and load-balancing solution 

* A collection of [additional PostgreSQL contrib extensions](https://www.postgresql.org/docs/14/contrib.html)

!!! seealso

    Blog Posts

    - [pgBackRest - A Great Backup Solution and a Wonderful Year of
      Growth](https://www.percona.com/blog/2019/05/10/pgbackrest-a-great-backup-solution-and-a-wonderful-year-of-growth/)
    - [Securing PostgreSQL as an Enterprise-Grade
      Environment](https://www.percona.com/blog/2018/09/21/securing-postgresql-as-an-enterprise-grade-environment/)

Percona Distribution for PostgreSQL is also shipped with the
[libpq](https://www.postgresql.org/docs/14/libpq.html) library. It
contains "a set of library functions that allow client programs to pass
queries to the PostgreSQL backend server and to receive the results of
these queries." [^1]

## Introduction


* [About Percona XtraBackup](intro.md)


* [How *Percona XtraBackup* Works](how_xtrabackup_works.md)


## Installation


* [Installing *Percona XtraBackup* on *Debian* and *Ubuntu*](installation/apt_repo.md)


* [Installing *Percona XtraBackup* on Red Hat Enterprise Linux and CentOS](installation/yum_repo.md)


* [Installing *Percona XtraBackup* from a Binary Tarball](installation/binary-tarball.md)


* [Compiling and Installing from Source Code](installation/compiling_xtrabackup.md)


## Run in Docker


* [Running Percona XtraBackup in a Docker container](installation/docker.md)


## Prerequisites


* [Connection and Privileges Needed](using_xtrabackup/privileges.md)


* [Configuring xtrabackup](using_xtrabackup/configuring.md)


## Backup Scenarios


* [The Backup Cycle - Full Backups](backup_scenarios/full_backup.md)


* [Incremental Backup](backup_scenarios/incremental_backup.md)


* [Compressed Backup](backup_scenarios/compressed_backup.md)


* [Encrypted Backup](backup_scenarios/encrypted_backup.md)


## User’s Manual


* [*Percona XtraBackup* User Manual](manual.md)


## Advanced Features


* [Throttling Backups](advanced/throttling_backups.md)


* [Lockless binary log information](advanced/lockless_bin-log.md)


* [Encrypted InnoDB Tablespace Backups](advanced/encrypted_innodb_tablespace_backups.md)


* [`lock-ddl-per-table` Option Improvements](advanced/locks.md)


## Tutorials, Recipes, How-tos


* [Recipes for xtrabackup](how-tos.md#recipes-xbk)


* [Recipes for innobackupex](how-tos.md#recipes-ibk)


* [How-Tos](how-tos.md#howtos)


* [Auxiliary Guides](how-tos.md#aux-guides)

## References


* [*Percona XtraBackup* 2.4 Release Notes](release-notes.md)


* [The xtrabackup Option Reference](xtrabackup_bin/xbk_option_reference.md)


* [The innobackupex Option Reference](innobackupex/innobackupex_option_reference.md)


* [The xbcloud Binary](xbcloud/xbcloud.md)


* [Exponential Backoff](xbcloud/xbcloud_exbackoff.md)


* [The xbcrypt binary](xbcrypt/xbcrypt.md)


* [The xbstream binary](xbstream/xbstream.md)


* [Known issues and limitations](known_issues.md)


* [Frequently Asked Questions](faq.md)


* [Glossary](glossary.md)


* [Index of files created by Percona XtraBackup](xtrabackup-files.md)


* [Trademark Policy](trademark-policy.md)


* [Version checking](version-check.md)


[^1]: <https://www.postgresql.org/docs/14/libpq.html>
