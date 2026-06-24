# Changelog

## [2026-01-20]
- **Fixed Undo/Redo System**: Corrected incorrect function calls and added safety checks for UI elements.
- **Fixed Pan Tool Bug**: Prevented the "Pan" tool from clearing the undo/redo history while moving the view. Added `name` property to `tool_pan` for proper tool identification.
- **Fixed Zoom Undo Bug**: Zoom operations no longer create undo/redo savepoints (zoom/pan are view operations, not data changes).
- **Improved Preview Mode**: Added support for camera movement (zoom and pan) while maintaining stable rendering.
- **Fixed Tool Initialization**: Resolved "t.init is not a function" errors when switching between certain tools.
- **Improved Stability**: Fixed several JavaScript syntax errors that were causing browser console errors.

## [2026-01-19]
- **Initial Setup**: Created static file server for Replit environment.
