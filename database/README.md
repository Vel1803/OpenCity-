# Database

PostgreSQL with the PostGIS extension for spatial/GIS queries.

## Planned Tables
- Departments
- Projects
- Assets
- Roads
- Pipelines
- Contractors
- Maintenance
- Notifications
- Citizens

## GIS Support
Project and asset locations are stored as PostGIS geometry columns, enabling spatial overlap queries used by the AI conflict-detection engine.

## Status
🚧 Schema not yet finalized — see [`docs/Database_Design.md`](../docs/Database_Design.md) for the current draft table list, and [`architecture/Database_ER.png`](../architecture/Database_ER.png) for the ER diagram once designed.
