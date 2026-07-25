# TODO: Sticky Section Headers + Section ID/Name Changes

## Steps

### Step 1: HTML — Move `.section-header` outside `.section-inner`
- [x] `#identity` section
- [x] `#career` section
- [x] `#SKILL` section (03 SKILL)
- [x] `#skill` section → became `#goal` (04 GOAL)
- [x] `#growth` section
- [x] `#richness` section → became `#vision` (06 VISION)

### Step 2: HTML — Rename #skill → #goal (section 04)
- [x] Changed id from `skill` to `goal`
- [x] Changed h2 text from `SKILL` to `GOAL`
- [x] Changed .section-sub text from `身につける力` to `目標`

### Step 3: HTML — Rename #richness → #vision (section 06)
- [x] Changed id from `richness` to `vision`
- [x] Changed h2 text from `RICHNESS` to `VISION`
- [x] Changed .section-sub text from `豊かさの再定義` to `ビジョン`

### Step 4: CSS — Add sticky styles for `.section-header`
- [x] Added `position: sticky; top: var(--header-h);` etc.
- [x] Handled `section--layer` header background
- [x] No padding-top adjustment needed (header is outside .section-inner)
- [x] Responsive compatibility maintained

### Step 5: Verify
- [x] All section headers moved outside .section-inner ✓
- [x] Section IDs and names updated correctly ✓
- [x] Sticky CSS added with proper z-index and background ✓
- [x] Nav links match section IDs (identity, career, SKILL, goal, vision) ✓

