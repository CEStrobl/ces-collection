# ces collection — Requirements

## Overview
**Purpose:**
Website displaying and linking to CES GitHub projects, providing a preview of each project, a link to the GitHub repo, and a link to the project website.

**Scope (In):**
- List of CES GitHub projects
- Project previews (screenshots or descriptions)
- Links to each project’s GitHub repo
- Links to each project’s website

**Scope (Out):**
- Not specified (TBD)

**Constraints:**
- Must be compatible on browsers and mobile devices (support both landscape and vertical views)

## Tech Environment / Assumptions
- Languages/Frameworks: HTML, CSS, JavaScript
- Runtime/Targets: Chrome, desktop and mobile browsers
- Restrictions: Needs to run at 40 FPS or more, can’t be laggy
- CI/Testing: Minimal testing needed (simple website)

## Requirements
### 3.1 Functional Requirements
1. The system shall display a list of CES GitHub projects.
2. The system shall show a preview (screenshot or description) for each project.
3. The system shall provide a link to each project’s GitHub repository.
4. The system shall provide a link to each project’s live website (if available).
5. The system shall adapt its layout for both desktop and mobile (landscape and vertical views).
6. The system shall display a gradient background (green and black, hacker aesthetic).
7. [Nice to Have] The system may display a 3D globe background if performance allows.

### 3.2 Non-Functional Requirements
- Performance: The system shall maintain at least 40 FPS during normal use.
- Reliability: The system shall load all project data without errors.
- Accessibility/UX: The system shall be navigable via keyboard. The system shall adapt to both desktop and mobile layouts.
- Other: The system shall load in under 2 seconds on broadband.


### 3.3 design requirments
(reference image in docs/collection.png)
1. background must be black
2. accent colors must be green
3. font pairing must be a monospace font like JetBrains paired with a readable one like Helvetica. 
4. the mono space font must be used for big headings to ensure attention grabbing.
5. the readable font must be used with blocks of text like the project paragraph description.
6. there must be a section dedicated to each project category
7. spacing and font heirarchy distinguish and separate project type categories (make a template for this ill fill in the individual peices later)
8. 

## Success Criteria
- [ ] All CES projects are listed with previews, GitHub links, and website links
- [ ] Layout adapts for desktop and mobile (landscape and vertical)
- [ ] Gradient background (green/black) is present
- [ ] System maintains 40+ FPS during normal use
- [ ] Loads in under 2 seconds on broadband
- [ ] No errors loading project data
- [ ] Keyboard navigation works
- [ ] (Optional) 3D globe background present and does not reduce FPS below 40
Metrics: 40+ FPS, <2s load time, all features work on desktop/mobile