---
layout: default
---
# Replication logger commands

All data-modification operations are written to the server's write-ahead log and are
not handled by a separate replication logger.

You can query the current state of the logger and fetch the latest changes
written by the logger with the `logger-state` method. The operations return the
state and data from the write-ahead log.

To query the latest changes logged by the replication logger, the HTTP interface
also provides the `logger-follow` method. This method should be used by
replication clients to incrementally fetch updates from an ArangoDB database.

To check what range of changes is available (identified by tick values), the HTTP
interface provides the methods `logger-first-tick` and `logger-tick-ranges`.
Replication clients can use the methods to determine if certain data (identified
by a tick *date*) is still available on the Leader.

{% docublock get_api_replication_logger_state, h2 %}
{% docublock get_api_replication_logger_follow, h2 %}
{% docublock get_api_replication_logger_first_tick, h2 %}
{% docublock get_api_replication_logger_tick_ranges, h2 %}
