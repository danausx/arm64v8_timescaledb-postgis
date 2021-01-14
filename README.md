# ARM64v8 timescaledb-postgis
Linux: ARM64v8 Alpine with Timescaledb 2.0.0 ; Postgis 3.1.0 ; GDAL 3.2.1 ; Postgres 12.5

## [PostgreSql 12.5](https://www.postgresql.org/) & [Postgis 3.1.0](https://postgis.net/) & [TimescaleDB 2.0.0](https://www.timescale.com/)

## TimescaleDB Overview

From: https://docs.timescale.com/latest/introduction

TimescaleDB is an open-source time-series database optimized for fast ingest and complex queries. It speaks "full SQL" and is correspondingly easy to use like a traditional relational database, yet scales in ways previously reserved for NoSQL databases.

Compared to the trade-offs demanded by these two alternatives (relational vs. NoSQL), TimescaleDB offers the best of both worlds for time-series data:

### Easy to Use
Full SQL interface for all SQL natively supported by PostgreSQL (including secondary indexes, non-time based aggregates, sub-queries, JOINs, window functions).

- Connects to any client or tool that speaks PostgreSQL, no changes needed.
- Time-oriented features, API functions, and optimizations.
- Robust support for Data retention policies.

## Docker Hub
If you don't want to wait the ~4h it takes to build this on a rpi you can download the image from [docker hub](https://hub.docker.com/r/thobi85/timescale-postgis/general/).

## Getting Started
You can find a good Getting Started Guide from Timescaledb with Docker on the [Timscale Documation Page](https://docs.timescale.com/latest/getting-started/installation/docker/installation-docker#react-docs)
