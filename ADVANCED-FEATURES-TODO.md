# Sprite Sheet Animator - Advanced Features TODO

## Current Status
✅ Basic animation (play/pause/reset)
✅ Frame stepping (prev/next)
✅ Keyboard shortcuts (Space, arrows, R)
✅ GIF export (working with gifshot)
✅ Frame download (PNG)
✅ Grid overlay
✅ Background color picker
✅ Reverse playback
✅ Speed & scale controls
✅ Frame counter

## Features to Implement

### 1. Timeline View (High Priority)
**What:** Horizontal strip showing all frame thumbnails
**How:** 
- Add scrollable div below canvas
- Render mini thumbnails (50x50px) for each frame
- Highlight current frame
- Click to jump to frame
**Estimated:** ~100 lines (CSS + JS)

### 2. Animation Presets (High Priority)
**What:** Save/load different frame ranges with names
**How:**
- Add preset panel with input field + save button
- Store in localStorage as JSON
- List saved presets with load/delete buttons
**Estimated:** ~80 lines (HTML + JS)

### 3. Onion Skinning (Medium Priority)
**What:** Show previous/next frames as semi-transparent overlay
**How:**
- Add checkbox + opacity slider
- Draw prev/next frames with reduced opacity before current frame
**Estimated:** ~40 lines (JS)

### 4. Loop Count Control (Medium Priority)
**What:** Play animation X times then stop
**How:**
- Add number input for loop count
- Track loops in animate() function
- Stop when count reached
**Estimated:** ~20 lines (JS)

### 5. Zoom Controls (Medium Priority)
**What:** 50%, 100%, 200%, Fit buttons
**How:**
- Add button group
- Adjust scale variable
- "Fit" calculates scale to fit canvas
**Estimated:** ~30 lines (JS)

### 6. Frame Filters (Low Priority)
**What:** Brightness, contrast, saturation sliders
**How:**
- Add sliders
- Apply CSS filters to canvas context
**Estimated:** ~50 lines (CSS + JS)

### 7. Export as ZIP (High Priority)
**What:** Download all frames as individual PNGs in ZIP
**How:**
- Use JSZip library (already added)
- Loop through frames, extract to canvas, add to ZIP
- Generate and download
**Estimated:** ~60 lines (JS)

### 8. Export Sprite Sheet (Medium Priority)
**What:** Rearrange frames into new grid layout
**How:**
- Add modal with cols/rows input
- Create new canvas with specified grid
- Draw all frames in new layout
- Download as PNG
**Estimated:** ~80 lines (JS)

### 9. CSS Sprite Code Generator (Low Priority)
**What:** Generate CSS code for using sprite sheet
**How:**
- Calculate frame positions
- Generate CSS classes with background-position
- Show in modal with copy button
**Estimated:** ~60 lines (JS)

### 10. Video Export (Low Priority)
**What:** Export as WebM video
**How:**
- Use MediaRecorder API
- Capture canvas during playback
- Download as video file
**Estimated:** ~100 lines (JS)

## Implementation Strategy

### Option A: Manual Implementation
You implement features one by one following this guide.

### Option B: Hire Developer
Share this TODO with a developer to implement.

### Option C: Incremental Updates
I implement 2-3 features at a time, test, commit, repeat.

### Option D: Use AI Coding Tool
Use Cursor/Codex/Claude Code to implement all features in one session.

## Next Steps
1. Choose implementation strategy
2. Prioritize which features you need most
3. Start with highest priority items

## Estimated Total Work
- **Lines of code:** ~620 lines
- **Time (manual):** 4-6 hours
- **Time (AI tool):** 30-60 minutes
- **Complexity:** Medium (mostly straightforward features)
