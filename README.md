# notes-must-have-c--dotnet-web-api-project
its a personal notes as a reminder which packages and patterns should be followed for proper working

## Project Target: c# - Web API - Dot Net Core 8 and Above
- Assembly Scanning for auto loading auto mapper profiles
- Assembly scanning for auto loading of repo and its related interface
- Assembly scanning for auto loading of service and its related interface
- Auto Migration of MainDBContext/Master DB Context
- Default Seed of Enum Values to Related Tables
- Default Seed of User Roles and Super Admin user
- Default Seed of Config Values
- Load and cache config values from Database
- 

## Improvements to include
- Separate System Data, Master Data, Business Data, Workflow Runtime, and Analytics Data (already discussed).
- Platform Services own their own tables (instead of business modules owning cross-cutting tables).
- ULID as the default primary key for business entities.
- Standard BaseEntity for audit and optimistic locking.
- Workflow Definition vs Workflow Runtime separation.
- Summary tables/materialized views for dashboards.
- Soft Delete only where appropriate (not every table).
- Partitioning strategy for large tables (audit logs, workflow history, notifications, etc.).
- Database indexing standards.
- Database naming conventions.
- Reference number generation through the Platform Sequence Service.
- File metadata stored in PostgreSQL while binaries live in Cloudflare R2.
- Backward compatibility strategy for future schema changes.
- Migration standards.
- Archiving and retention policy.
