# WindBar Content Types

WindBar's creator model is designed around small, composable content types rather than one monolithic "skin" format.

## Layout Profile
Defines module arrangement, ordering, visibility, and related layout choices. This is expected to be one of the earliest safe community-shareable formats.

## Visual Theme
Defines appearance/material character independently of taskbar and Start structure.

## Color Scheme
A variant belonging to a Visual Theme, such as Light/Dark or a historical theme's color variants.

## Start Layout
Defines user content/arrangement inside a supported Start Style. It does not implement a new Start Style by itself.

## Experience Preset
A one-time bundle referencing compatible Design Language, Visual Theme, Color Scheme, Taskbar Style, Start Style, Layout Profile, and behavior defaults. Presets do not continuously own settings after application.

## Plugin
Executable extension architecture intended to provide optional functionality such as Modules, widgets, flyouts, providers, integrations, and plugin-specific settings.

Public arbitrary third-party plugin loading is not part of WindBar 1.0's current plan. A public SDK/security model will be documented before executable community plugins are treated as a supported ecosystem.

## Module
A visible WindBar component. Core examples include Apps and Clock; future plugin-provided examples might include performance, weather, or other compact information/interaction surfaces.

## Widget
A user-facing category for a compact informational/interactive Module. WindBar does not currently plan a separate widget extension architecture; widgets should fit the Module/plugin model.

## Design Language, Taskbar Style, and Start Style
These are product-level structural/rendering systems rather than simple content files. Community proposals may influence them, but their public extension contracts are not defined at this time.
