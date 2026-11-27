# Repository synchronization

Synchronization imports Markdown files from the configured source folder and mounts them under the selected project path.

## Expected outcomes

- New remote page: imported.
- Updated untouched page: refreshed.
- Unchanged page: skipped.
- Locally edited and remotely changed page: marked as a conflict.
- Remotely removed untouched page: removed locally.

Credentials remain in Environment Service and are scoped to the calling service, tenant, user, and documentation source.

