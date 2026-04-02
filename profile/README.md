# Lasect

Lasect is a suite of tools for teams running Postgres in production. We're building two projects that cover the full operational surface: infrastructure control and workload intelligence.

Orca is a control plane for Postgres infrastructure. It handles provisioning, configuration, sharding, extensions, backups, across your environments. It uses battle-tested tools under the hood without re-inventing the wheel.

Tetra sits on top of your Postgres workloads and gives you visibility into query behavior, performance patterns, anomalies, and resource usage over time.

### We also work on:

*   **[discodb](https://github.com/lasect/discodb)**: a relational database stored 100% in a discord guild built with go
*   **[pg_turret](https://github.com/lasect/pg_turret)**: real-time postgres log streaming to external destinations.
*   **[rlsmon](https://github.com/lasect/rlsmon)**: rls debugger & simulator for postgres
*   **[pg_tenant](https://github.com/lasect/pg_tenant)**: a poc for handling multitenancy in postgres with an extension
*   **[pg_aim](https://github.com/lasect/pg_aim)**: automated index management in pgrx to learn more about internals.
*   **[benjdickenmarks](https://github.com/lasect/benjdickenmarks)**: general benchmarks for postgres, starting with text search.

### Misc Experiments
*   **[syncyphus](https://github.com/lasect/syncyphus)**: obsidian knowledge graph sync powered by [helixdb](https://www.helix-db.com/)
*   **[ambala](https://github.com/lasect/ambala)**: contextual search engine powered by [helixdb](https://www.helix-db.com/)
*   **[dymunim](https://github.com/lasect/dymunim)**: postgres-native execution layer powered by cloudflare [dynamic workers](https://developers.cloudflare.com/dynamic-workers/)
