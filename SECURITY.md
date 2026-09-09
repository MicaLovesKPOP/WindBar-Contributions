# Security for Creator Content

Creator content falls into two broad risk classes.

## Data/content-only
Examples include Layout Profiles, Visual Themes, Color Schemes, Start layouts, and Experience Presets. These should ultimately be schema-validated and must not rely on arbitrary executable code.

## Executable plugins
Plugins can carry much greater risk. WindBar does not currently treat arbitrary third-party executable plugins as a supported public ecosystem.

Before that changes, WindBar intends to define a compatibility, capability/permission, failure-isolation, packaging, update-verification, and safe-mode model.

Do not present community plugins as officially trusted or supported unless WindBar has explicitly adopted them.

Security-sensitive reports should not include secrets or personal diagnostic data in public issues.
