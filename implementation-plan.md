# Advanced Features Implementation Plan

## Phase 1: UI Additions (CSS + HTML)
- Timeline strip below canvas (horizontal scrollable frame thumbnails)
- Presets panel (save/load/delete buttons + preset list)
- Onion skinning controls (checkbox + opacity slider)
- Zoom controls (50%, 100%, 200%, Fit buttons)
- Filter controls (brightness, contrast, saturation sliders)
- Loop count input
- Export buttons (ZIP, Sprite Sheet, CSS Code, Video)

## Phase 2: JavaScript Functions
- Timeline rendering and click handlers
- Preset save/load to localStorage
- Onion skin overlay rendering
- Zoom level management
- Filter application (CSS filters on canvas)
- Loop counter logic
- ZIP export with JSZip
- Sprite sheet regeneration
- CSS code generation
- Video recording with MediaRecorder

## Phase 3: Integration
- Wire up all event listeners
- Test all features
- Ensure Obsidian theme consistency

## Estimated additions:
- ~200 lines CSS
- ~400 lines JavaScript
- ~100 lines HTML
