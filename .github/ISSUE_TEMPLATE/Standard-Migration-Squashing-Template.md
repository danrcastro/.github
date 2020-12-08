---
name:  Migration Squash
about: Use this template to create an issue to squash all migrations
labels: Technical
---

# Description
We have 10 or more migration files

## Negative Impact:
This causes QA script, and general project initialization to slow down costing us developer hours

# Proposed Solution:
Squash migrations down into the init_schema directory of the migrations directory. 
Create new migration classes as necessary.

## Acceptance Criteria
- [ ] All migrations created prior to the creation of this issue are squashed down into the initial_migration folder.

## Announcement Message
devchat: All migrations have been squashed, please rebase to master to have a consistent project initialization.
