# WindBar Creator Guide

This guide explains the intended creator model before all public formats are finalized.

## The core idea

WindBar separates different customization layers so creators do not need to replace the entire experience to change one part of it.

The long-term model includes:

- **Design Language** — UI grammar such as control geometry, spacing, typography treatment, icon language, and interaction conventions.
- **Visual Theme** — material/appearance character such as Aero- or Luna-like styling.
- **Color Scheme** — a variant belonging to a Visual Theme.
- **Taskbar Style** — the structural/model characteristics of a taskbar.
- **Start Style** — the structural/model characteristics of Start.
- **Layout Profile** — WindBar module arrangement and visibility.
- **Behavior** — interaction/default behavior policies.
- **Experience Preset** — a one-time bundle of compatible choices across those layers.

A creator should be able to target one layer without unnecessarily owning the others.

## Examples

A theme creator might make a Visual Theme that works with WindBar's current system Design Language.

A layout creator might make a vertical productivity Layout Profile without changing the user's theme or Start Style.

A future plugin creator might provide one or more Modules, flyouts, settings pages, or integrations without replacing core WindBar infrastructure.

## System and Auto

WindBar reserves **System** for matching the installed operating system or corresponding OS preference.

WindBar reserves **Auto** for values resolved from another WindBar setting/context.

Creators should not invent conflicting meanings for these terms.

## Current status

Public package schemas and plugin APIs are not stable yet. Use this repository to follow the direction, examples, and eventual specifications. Files under `schemas/` and `examples/` will state when a format becomes stable enough to target.
