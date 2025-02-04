---
layout: default
description: The full ArangoDB package ships with the following programs and tools
---
Programs & Tools
================

The full ArangoDB package ships with the following programs and tools:

| Executable name | Brief description |
|-----------------|-------------------|
| `arangod`       | [ArangoDB server](programs-arangod.html). This server program is intended to run as a daemon process / service to serve the various client connections to the server via TCP / HTTP. It also provides a [web interface](programs-web-interface.html).
| `arangosh`      | [ArangoDB shell](programs-arangosh.html). A client that implements a read-eval-print loop (REPL) and provides functions to access and administrate the ArangoDB server.
| `arangodb`      | [ArangoDB Starter](programs-starter.html) for easy deployment of ArangoDB instances.
| `arangodump`    | Tool to [create backups](programs-arangodump.html) of an ArangoDB database.
| `arangorestore` | Tool to [load backups](programs-arangorestore.html) back into an ArangoDB database.
| `arangobackup`  | Tool to [perform hot backup operations](programs-arangobackup.html) on an ArangoDB installation.
| `arangoimport`  | [Bulk importer](programs-arangoimport.html) for the ArangoDB server. It supports JSON and CSV.
| `arangoexport`  | [Bulk exporter](programs-arangoexport.html) for the ArangoDB server. It supports JSON, CSV and XML.
| `arangobench`   | [Benchmark and test tool](programs-arangobench.html). It can be used for performance and server function testing.
| `arangovpack`   | Utility to validate and [convert VelocyPack](programs-arangovpack.html) and JSON data.
| `arangoinspect` | [Inspection tool](programs-arangoinspect.html) that gathers server setup information.

The client package comes with a subset of programs and tools:

- `arangosh`
- `arangoimport`
- `arangoexport`
- `arangodump`
- `arangorestore`
- `arangobackup`
- `arangobench`
- `arangoinspect`
- `arangovpack`

Additional tools which are available separately:

| Name            | Brief description |
|-----------------|-------------------|
| [Foxx CLI](programs-foxx-cli.html) | Command line tool for managing and developing Foxx services
| [kube-arangodb](deployment-kubernetes.html) | Operators to manage Kubernetes deployments
| [Oasisctl](arangograph/oasisctl.html) | Command-line tool for managing the ArangoGraph Insights Platform
