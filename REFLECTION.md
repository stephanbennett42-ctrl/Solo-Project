# Project Reflection — Tech Creator Portfolio

### 1. How did setting universal `box-sizing: border-box` simplify layout calculations during development?
It made layout styling much easier because padding and borders stay inside an element's total width, preventing unexpected page overflow.

### 2. What challenges did you face when extracting exact margin, padding, and gap spacing from Figma?
Fixed pixel measurements in Figma look great on desktop screens, but on mobile devices, they can cause overflow. Adjusting fixed pixels into flexible gaps for smaller screens took trial and error.

### 3. How did you decide between using `flex-wrap` vs. explicit `@media` queries for card layout responsiveness?
I used dynamic CSS Grid wrapping for the project cards so they automatically fit any screen size, and reserved `@media` queries for structural shifts, like stacking the hero section vertically on mobile.

### 4. What strategies did you use to keep your CSS stylesheet organized and easy to maintain?
I split my CSS into separate smaller files (`navbar.css`, `hero.css`, `variables.css`) and linked them through `style.css`. I also used CSS variables for colors so theme updates could be done in one place.

### 5. What would you improve about your CSS layout structure in future projects?
Next time, I will build with a mobile-first approach (styling for phones first, then adding desktop rules) and refine the mobile drawer entry animations.