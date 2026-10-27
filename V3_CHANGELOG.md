# V3 Changelog

## Development checkpoint — post master-prompt changes
- Added Workout Library CRUD fields and category filtering.
- Added selection of saved library definitions in Plan and category-specific Yoga/Cardio sessions.
- Added Calendar empty-date creation and date-specific plan visibility.
- Extended XLSX template/export/import with a Calendar Date column, validation, selected-plan-day import, missing-library-definition creation and date-specific override mapping.
- Added session completion records, timestamps, side-stage metadata, weekly/monthly progress KPIs, an 8-week activity trend, history filtering and CSV export.
- Added health measurement input-range checks, source/record timestamps and inactivity locking.
- Replaced broad Android storage access with a Storage Access Framework folder picker and persisted URI grants; removed broad file-management permission from the manifest patch.
- Kept connected health provider integration and the wider data-integrity/backup/production-release workstream deferred per user instruction.
- Added static structure checks and refreshed acceptance, progress, limitations and build documentation.
- No Android APK build or physical-device test is claimed.
