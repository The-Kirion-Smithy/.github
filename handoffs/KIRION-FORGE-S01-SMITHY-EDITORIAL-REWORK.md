# KIRION FORGE: MAINTAINER → CODE WRITER — S01 SMITHY ORGANIZATION PROFILE EDITORIAL REWORK

## MAINTAINER DISPOSITION

```text
REWORK
```

The current public Smithy profile has the correct organizational intent but the wrong visual language.

Do **not** iterate on the existing neon / ASCII / cyber-HUD direction.

This lane replaces it.

The target is a public GitHub organization profile that feels like the **engineering institution behind Kirch's portfolio**: editorial, human, restrained, photographic, typographically confident, and obviously built by a real engineering practice rather than generated from a generic "cybersecurity AI" visual recipe.

---

# 0. AUTHORITY

Repository:

```text
The-Kirion-Smithy/.github
```

Human Technical Authority:

```text
Kirch Ivan Balite
```

Maintainer:

```text
ChatGPT / KIRION FORGE MAINTAINER
```

Execution role:

```text
KIRION FORGE: CODE WRITER
```

Live product base independently verified before this handoff:

```text
main
@d47b65dadc45cb3a8fbbe46c9fe3b3d193bf9ed8
```

Current profile file:

```text
profile/README.md
```

Current rejected presentation assets:

```text
profile/assets/smithy-header.svg
profile/assets/engineering-loop.svg
```

Authorized execution branch already created from the exact product base:

```text
KIRION-FORGE-S01-SMITHY-EDITORIAL-REWORK
```

This branch begins from:

```text
d47b65dadc45cb3a8fbbe46c9fe3b3d193bf9ed8
```

and contains this Maintainer handoff as the only bootstrap mutation before product work.

Do **not** create another branch.

Do **not** reset, rebase, or remove the handoff commit.

Before changing `profile/**`, verify:

```text
1. current branch =
   KIRION-FORGE-S01-SMITHY-EDITORIAL-REWORK

2. branch ancestry descends from =
   d47b65dadc45cb3a8fbbe46c9fe3b3d193bf9ed8

3. main still =
   d47b65dadc45cb3a8fbbe46c9fe3b3d193bf9ed8

4. profile/README.md is still product-equivalent to the product base

5. profile/assets/smithy-header.svg is still the neon ASCII hero

6. profile/assets/engineering-loop.svg is still the animated neon loop
```

If any product file has drifted unexpectedly:

```text
STOP
REPORT DRIFT
DO NOT GUESS
DO NOT RESET
DO NOT REBASE
DO NOT FORCE PUSH
```

No merge.
No promotion.
No deployment.
No mutation of `main`.

---

# 1. LANE

```text
S01 — SMITHY ORGANIZATION PROFILE EDITORIAL IDENTITY REWORK
```

This lane owns only:

```text
The-Kirion-Smithy/.github

profile/README.md
profile/assets/**
handoffs/KIRION-FORGE-S01-SMITHY-EDITORIAL-REWORK.md
```

The handoff file itself is frozen evidence and must not be rewritten by Code Writer unless a factual typo blocks execution.

This is a:

```text
PUBLIC IDENTITY
+
EDITORIAL PRESENTATION
+
STATIC ASSET
```

lane.

This is **not**:

```text
Forge architecture work
organization permissions work
organization/team configuration
GitHub Projects work
repository governance redesign
CI/CD work
product-repository work
application development
AI-agent feature work
```

---

# 2. CURRENT STATE — WHAT IS ACTUALLY WRONG

The current `profile/README.md` has a useful information hierarchy:

```text
hero
→ Smithy identity
→ Orchestrator
→ Kirions
→ engineering loop
→ ecosystem footer
```

The problem is the **presentation system**.

The current hero asset explicitly contains:

```text
ASCII portrait of Kirch
black/green "void"
neon/acid gradient
grid pattern
green glow filter
scan animation
trace animation
pulse animation
monospace-first treatment
cyber-HUD corner language
```

The current method asset repeats:

```text
black/green gradient
neon line
glow
animated route trace
animated node pulse
monospace labels
HUD corners
```

That combination reads as:

```text
generic hacker aesthetic
AI-generated cybersecurity branding
terminal cosplay
```

before it reads as:

```text
serious engineering organization
people
craft
discipline
evidence
```

The lane must correct that at the system level.

Do **not** merely:

```text
reduce the glow
change the green
make the ASCII portrait cleaner
slow the animation
make the loop flatter
```

The entire visual grammar is rejected.

---

# 3. EXTERNAL VISUAL AUTHORITY — KIRCH PORTFOLIO

Use the existing portfolio as the **primary design authority**.

Reference repository:

```text
Kirch-Nairu/kirch-webportfolio
```

Reference branch:

```text
feature/premium-portfolio-site
```

Reference branch head independently verified:

```text
eb8e4e470014a6e818f74a255ddf7b5fb8e111c9
```

The portfolio repository is **read-only** in this lane.

Do not modify it.

The implementation must study at least:

```text
app/layout.tsx
app/globals.css
public/images/kirich.jpg
```

before producing Smithy assets.

The portfolio establishes the following actual design language.

## Typography

Primary:

```text
Manrope
```

Editorial / italic emphasis:

```text
Instrument Serif
```

The portfolio uses:

```text
Manrope
→ navigation
→ body
→ labels
→ metadata
→ large primary headlines

Instrument Serif
→ selective italic/editorial emphasis
```

Do not replace this with:

```text
monospace-first branding
Orbitron
techno display fonts
terminal fonts
generic geometric "AI startup" fonts
```

## Core palette

Authoritative portfolio variables:

```text
--ink:         #0b0c0a
--ink-soft:    #131511

--paper:       #ece9df
--paper-soft:  #dedbd1

--text:        #f4f2eb
--muted:       #a2a39b

--dark-text:   #161714
--dark-muted:  #62645e

--accent:      #b8d96d
--accent-dark: #56751f
```

The accent is editorial punctuation.

It is **not neon**.

Target overall distribution:

```text
~55% dark ink / near-black
~35% warm paper / neutral
<10% lime accent
```

## Portfolio composition patterns to translate

Borrow:

```text
large confident sans-serif headlines
tight tracking
short line lengths
low line-height on display typography
dark hero
warm-paper editorial section
asymmetric split layouts
real portrait photography
thin rules
small numbered section labels
generous whitespace
restrained microcopy
quiet metadata
real visual hierarchy
```

Do not copy:

```text
portfolio navigation
portfolio product sections
contact CTA
Salryn content
Kirjane Labs content
personal portfolio IA
website interaction patterns that do not translate to GitHub README
```

This is a translation of the design system.

Not a clone of the website.

---

# 4. GOVERNING VISUAL RULE

> **The Smithy must look like the engineering institution behind Kirch's portfolio — not like a hacker-themed AI demo.**

Every implementation choice must be tested against that sentence.

Secondary rule:

> **People are the primary visual signal. Engineering discipline is the secondary signal. Technology decoration is not a signal.**

---

# 5. GITHUB RENDERING STRATEGY

GitHub organization profiles do not provide the same CSS/runtime environment as the portfolio.

Therefore use this architecture:

```text
NATIVE MARKDOWN / SAFE README HTML
for:
- semantic headings
- links
- accessible text
- concise body copy
- fallback meaning

+

PRE-RENDERED STATIC EDITORIAL CANVASES
for:
- exact typography
- photographic composition
- portfolio-grade hero
- Jane member feature
- optional static method composition
```

Do not attempt to rebuild the portfolio using:

```text
HTML table hacks
badge walls
nested markdown tables for layout
terminal blocks as decoration
inline neon SVG systems
emoji-heavy composition
```

Static assets must work as presentation, while the README remains meaningful without them.

---

# 6. PORTRAIT SOURCES

## 6.1 Kirch Ivan Balite

Canonical existing portrait source:

```text
Kirch-Nairu/kirch-webportfolio
feature/premium-portfolio-site
public/images/kirich.jpg
```

Use the actual existing portrait.

Do not:

```text
AI-generate Kirch
redraw Kirch
turn Kirch into ASCII
add circuit overlays
add green scan lines
add glitch effects
add synthetic cyber lighting
replace the real portrait with an illustration
```

Allowed:

```text
desaturation
monochrome treatment
controlled crop
subtle contrast correction
editorial framing
```

The portrait should remain recognizably photographic.

## 6.2 Jane Katheryn Roselle Ryn

Canonical identity:

```text
Jane Katheryn Roselle Ryn
GitHub: Kirion-Jane
```

The current connected GitHub profile exposes a legitimate current profile photograph.

Use that current GitHub profile photograph as Jane's visual source unless a dedicated Smithy portrait already exists when implementation begins.

Preferred source:

```text
https://avatars.githubusercontent.com/u/335897759?v=4
```

Download and store a stable local copy in the Smithy repository so the final profile asset is not dependent on a volatile profile-avatar URL.

Suggested local source asset:

```text
profile/assets/jane-katheryn-roselle-ryn.jpg
```

Do not:

```text
AI-generate Jane
invent Jane's face
replace Jane with an illustration
invent a job title
invent technical specialties
invent a biography
invent authority or seniority
invent employment claims
invent pronouns
invent achievements
```

Authorized factual public copy for this lane:

```text
JANE KATHERYN ROSELLE RYN

THE FIRST KIRION.

@Kirion-Jane
```

Profile link:

```text
https://github.com/Kirion-Jane
```

If a legitimate portrait cannot be acquired:

```text
STOP
RETURN TO MAINTAINER
DO NOT SUBSTITUTE GENERATED ART
```

---

# 7. TARGET PROFILE ARCHITECTURE

The final GitHub organization profile should be short enough that the native GitHub organization surface and repository list can continue naturally below it.

Target hierarchy:

```text
HERO
↓
01 — THE SMITHY
↓
02 — KIRIONS
↓
03 — METHOD
↓
ECOSYSTEM FOOTER
```

Approximate desktop reading order:

```text
┌──────────────────────────────────────────────────────────────┐
│ THE SHARED ENGINEERING FLOOR                                │
│                                                              │
│ KIRION                           [KIRCH PORTRAIT]             │
│ SMITHY                                                       │
│                                                              │
│ Where intent becomes                                         │
│ working systems.                                             │
│                                                              │
│ concise supporting statement                                 │
│                                                              │
│ ORCHESTRATED BY KIRCH IVAN BALITE                            │
└──────────────────────────────────────────────────────────────┘


01 — THE SMITHY

Structure before spectacle.
Evidence before confidence.

[short explanatory copy]


02 — KIRIONS

┌──────────────────────────────────────────────────────────────┐
│ [JANE PORTRAIT]       JANE KATHERYN ROSELLE RYN             │
│                       THE FIRST KIRION.                       │
│                       @Kirion-Jane                            │
│                                                              │
│                       VIEW PROFILE →                          │
└──────────────────────────────────────────────────────────────┘

Others are still being forged.


03 — METHOD

01 UNDERSTAND
02 PLAN
03 BUILD
04 VERIFY
05 DEPLOY
06 OPERATE
07 LEARN

RETURN

Every output comes back as evidence for the next pass.


──────────────────────────────────────────────────────────────

PART OF THE KIRION ECOSYSTEM
COGNITION · FORGE · BREAKOUT
```

---

# 8. SECTION 1 — HERO

The current `smithy-header.svg` is rejected.

Replace it with a real photographic editorial hero.

Preferred new assets:

```text
profile/assets/smithy-hero-desktop.png
profile/assets/smithy-hero-mobile.png
```

Suggested desktop artboard:

```text
1600 × 800
```

Acceptable range:

```text
1600 × 760
through
1600 × 840
```

Suggested mobile artboard:

```text
900 × 1200
```

The exact dimensions are Code Writer-owned if visual testing demonstrates a better ratio.

## Desktop composition

Target:

```text
58–62% typography / negative space
38–42% portrait
```

Kirch portrait on the right.

Typography on the left.

No card shell around the hero.

No giant rounded rectangle.

No fake browser window.

No device mockup.

No border glow.

No HUD frame.

No grid.

No ASCII.

No fake telemetry.

## Hero copy — frozen

Kicker:

```text
THE SHARED ENGINEERING FLOOR
```

Primary identity:

```text
KIRION
SMITHY
```

Editorial emphasis:

```text
Where intent becomes working systems.
```

Support:

```text
The engineering floor of the Kirion ecosystem.
Understand the problem, build deliberately,
verify the result, and return evidence
the next pass can trust.
```

Metadata:

```text
ORCHESTRATED BY KIRCH IVAN BALITE
```

Do not add more hero paragraphs.

Do not add CTA buttons.

Do not add fake status metrics.

Do not add "AI-powered".

## Hero visual behavior

The title must dominate.

The portrait must feel human and editorial.

The accent must be sparse.

Preferred:

```text
KIRION / SMITHY
→ Manrope

Where intent becomes working systems.
→ Instrument Serif, selective italic

kicker / metadata
→ Manrope, small uppercase
```

Avoid letter-spacing that creates "terminal UI" texture.

The hero should look closer to the existing Kirch portfolio hero than to the current Smithy banner.

---

# 9. SECTION 2 — THE SMITHY

Use native Markdown / safe README HTML for the actual semantic text.

Section label:

```text
01 — THE SMITHY
```

Headline:

```text
Structure before spectacle.
```

Editorial line:

```text
Evidence before confidence.
```

Body — frozen:

```text
The Smithy is where Kirion work is bounded, built,
reviewed, and returned. It exists to keep engineering
intent clear while implementation moves fast enough
to matter.
```

Do not add another manifesto paragraph.

Do not add vague claims about:

```text
world-class engineering
innovation
disruption
next-generation systems
cutting-edge AI
```

Whitespace is allowed to carry hierarchy.

---

# 10. SECTION 3 — KIRIONS / JANE PROFILE

This is a required major upgrade.

The current profile only gives Jane:

```text
a Markdown heading/link
"The first Kirion."
"Others are still being forged."
```

That is insufficient.

Jane must be visually present as a real member of the Smithy.

Preferred assets:

```text
profile/assets/jane-profile-desktop.png
profile/assets/jane-profile-mobile.png
```

Suggested desktop artboard:

```text
1600 × 680
```

Suggested mobile artboard:

```text
900 × 1100
```

## Jane composition

Target desktop:

```text
40–45% portrait
55–60% identity / negative space
```

Preferred treatment:

```text
actual Jane portrait
warm-paper or restrained ink surface
large full name
small KIRION 01 index
Instrument Serif "The first Kirion."
quiet @Kirion-Jane metadata
one simple profile-link cue
```

Do not make Jane look like a staff-directory card.

Do not surround her with skill chips.

Do not invent role tags.

Do not add fake quotes.

Do not add an AI-generated biography.

## Required native fallback copy

Keep Jane's identity available outside the image.

Use approximately:

```markdown
## 02 — KIRIONS

### [Jane Katheryn Roselle Ryn](https://github.com/Kirion-Jane)

**The first Kirion.**

[View Jane's GitHub profile →](https://github.com/Kirion-Jane)

*Others are still being forged.*
```

Exact heading levels may be adjusted to fit the final README hierarchy.

The factual content may not be expanded beyond evidence available in this lane.

---

# 11. SECTION 4 — METHOD

The current heading:

```text
THE FLOOR NEVER STOPS AT “DONE”
```

and animated `engineering-loop.svg` presentation are rejected.

Preserve the underlying engineering idea.

Replace the presentation.

New section:

```text
03 — METHOD
```

Canonical stages remain exactly:

```text
01 UNDERSTAND
02 PLAN
03 BUILD
04 VERIFY
05 DEPLOY
06 OPERATE
07 LEARN
```

Closing principle:

```text
RETURN

Every output comes back as evidence for the next pass.
```

The old paragraph:

```text
Every output returns as evidence. Every lesson sharpens the next build.
That is the Smithy: a living engineering floor, not a documentation wall.
```

may be retired.

The replacement is intentionally tighter.

## Method visual options

Preferred first option:

```text
native typographic process
+
thin rules
+
numbered stages
```

Optional only if it materially improves the result:

```text
profile/assets/smithy-method-desktop.png
profile/assets/smithy-method-mobile.png
```

If a graphic is used:

```text
static only
no animation
no glow
no node pulse
no trace line
no HUD corners
no terminal styling
no fake dashboard
```

A simple editorial sequence is better than another "engineering diagram".

---

# 12. FOOTER

Keep the ecosystem relationship.

Use a minimal ending:

```text
PART OF THE KIRION ECOSYSTEM

COGNITION · FORGE · BREAKOUT
```

Do not add badges.

Do not add social icon rows.

Do not add a giant footer canvas unless the native version is visibly inadequate.

The GitHub page itself already provides organization chrome.

The profile should know when to stop.

---

# 13. TYPOGRAPHY CONTRACT

High-fidelity canvases must use the portfolio typography where technically available:

```text
Manrope
Instrument Serif
```

Preferred role assignment:

```text
Manrope
→ primary display titles
→ body
→ labels
→ metadata

Instrument Serif
→ one selective editorial phrase
→ restrained italic emphasis
```

Do not use Instrument Serif for long body paragraphs.

Do not create a three-font system.

Do not use monospace as identity.

Do not use "tech typography" merely because this is engineering.

## Font rendering implementation

The repository itself does **not** need a frontend runtime.

To produce final raster canvases, Code Writer may use temporary local rendering methods such as:

```text
temporary HTML/CSS render
browser screenshot
locally available raster tooling
temporary script outside committed product scope
```

Do not commit font files.

Do not commit a package/toolchain solely to render the images.

If the exact fonts cannot be rendered in the execution environment, report the limitation before substituting a materially different typography system.

Do not silently replace Manrope / Instrument Serif with a random pair.

---

# 14. PHOTOGRAPHY CONTRACT

Photographs should feel:

```text
editorial
human
quiet
controlled
deliberate
```

Preferred treatment:

```text
monochrome or gently desaturated
soft contrast
clear facial detail
controlled crop
real texture
```

Avoid:

```text
AI smoothing
beauty-filter look
cyber tint
green overlay
vignette abuse
particles
noise overlays
CRT texture
glitch
chromatic aberration
circuitry
matrix texture
```

People are not technology decoration.

---

# 15. COLOR CONTRACT

Use the portfolio family.

Dark:

```text
#0b0c0a
#131511
```

Paper:

```text
#ece9df
#dedbd1
```

Text:

```text
#f4f2eb
#161714
#a2a39b
#62645e
```

Accent:

```text
#b8d96d
#56751f
```

Allowed accent uses:

```text
section index
single editorial phrase
small cue
small rule
small metadata highlight
```

Never:

```text
glow
halo
neon stroke
full-page acid green
green-on-black code texture
```

---

# 16. SHAPE / SPACING CONTRACT

The portfolio uses hierarchy through whitespace rather than container proliferation.

Use:

```text
large negative space
thin rules
simple image edges
restrained composition
```

Avoid:

```text
card carnival
pill spam
rounded-everything
nested panels
floating rectangles
fake browser windows
thick borders
drop-shadow stacks
```

Recommended visual radius:

```text
0–12px
```

Do not recreate the current giant rounded neon asset frame.

---

# 17. STATIC ASSET FORMAT

Preferred final assets:

```text
PNG
```

because exact typography and photography must survive GitHub rendering consistently.

Use enough resolution for desktop retina-like sharpness while keeping reasonable repository size.

Target approximately:

```text
hero desktop       <= 2.5 MB preferred
hero mobile        <= 2.0 MB preferred
Jane desktop       <= 2.5 MB preferred
Jane mobile        <= 2.0 MB preferred
method assets      <= 1.5 MB each if used
```

These are quality targets, not hard failure thresholds.

Do not destroy photographic quality merely to hit them.

Avoid JPEG for canvases containing substantial type unless visual testing proves it remains clean.

---

# 18. README IMAGE DELIVERY

Use unique final asset filenames.

Do not keep commit-SHA-pinned raw URLs for active assets merely to fight GitHub cache.

Preferred:

```text
relative repository paths
```

or stable raw URLs only if required by GitHub organization-profile rendering.

Where GitHub supports it reliably, use a responsive `<picture>`:

```html
<picture>
  <source media="(max-width: 640px)" srcset="./assets/smithy-hero-mobile.png">
  <img width="100%" alt="The Kirion Smithy — shared engineering floor, with Kirch Ivan Balite" src="./assets/smithy-hero-desktop.png">
</picture>
```

If GitHub strips or mishandles the media source, prefer one robust responsive image rather than introducing brittle hacks.

The rendered result is the authority.

Not the theoretical HTML.

---

# 19. ACCESSIBILITY CONTRACT

Critical information must not exist only inside raster artwork.

Required:

```text
meaningful alt text
native Kirch name in README text
native Jane name in README text
native Jane profile link
native section headings
adequate contrast
no animation
no color-only meaning
```

Recommended alt text:

Hero:

```text
The Kirion Smithy — shared engineering floor, with Kirch Ivan Balite
```

Jane:

```text
Jane Katheryn Roselle Ryn — the first Kirion
```

Method if rasterized:

```text
Kirion method — Understand, Plan, Build, Verify, Deploy, Operate, Learn, Return
```

The profile must remain understandable when images fail.

---

# 20. RESPONSIVE CONTRACT

Review at minimum:

```text
1440-class desktop
1280-class laptop
768 tablet
390 mobile
360 narrow mobile
```

## Hero

Desktop:

```text
split typography / portrait
```

Mobile:

```text
stacked editorial composition
large title remains readable
portrait receives deliberate crop
no desktop asset simply shrunk until text becomes microscopic
```

## Jane

Desktop:

```text
portrait + identity split
```

Mobile:

```text
portrait first
identity second
full name legible
"The first Kirion." legible
```

If GitHub responsive picture behavior is unreliable, produce one artboard that remains strong at both wide and narrow rendering rather than forcing an unsupported implementation.

---

# 21. PROHIBITED COPY

Do not add:

```text
next-gen engineering
revolutionizing software
elite AI workforce
unleashing innovation
cutting-edge intelligence
digital forge of the future
where code meets destiny
world-class engineering
AI-powered engineering floor
autonomous engineering army
```

Do not add filler just because a visual surface feels empty.

Do not write marketing paragraphs to justify the design.

The profile should sound like an engineering organization, not a pitch deck.

---

# 22. ABSOLUTELY PROHIBITED VISUAL LANGUAGE

No:

```text
ASCII portraits
Matrix rain
source-code texture
random binary
terminal windows
console prompt decoration
cyber HUD corners
scanner lines
scan animation
animated route traces
node pulses
green glow
neon
acid gradients
tech grids
fake telemetry
fake metrics
hex dumps
CRT effects
glitch
AI-generated human portraits
```

If any final surface looks like it belongs in a generic "cybersecurity wallpaper" search result:

```text
REWORK IT
```

before return.

---

# 23. FILE OWNERSHIP

Expected modified:

```text
profile/README.md
```

Expected new:

```text
profile/assets/smithy-hero-desktop.png
profile/assets/smithy-hero-mobile.png

profile/assets/jane-katheryn-roselle-ryn.jpg
profile/assets/jane-profile-desktop.png
profile/assets/jane-profile-mobile.png
```

Optional new only if justified:

```text
profile/assets/kirch-ivan-balite.jpg
profile/assets/smithy-method-desktop.png
profile/assets/smithy-method-mobile.png
```

Kirch's local portrait copy is optional because the source already exists in the portfolio repo; however a stable local Smithy copy is acceptable if it improves reproducibility.

Expected removed once no longer referenced:

```text
profile/assets/smithy-header.svg
profile/assets/engineering-loop.svg
```

Do not retain obsolete neon assets merely because they are historical.

Git history is the archive.

---

# 24. NO TOOLCHAIN EXPANSION

Do not add:

```text
package.json
package-lock.json
node_modules
React
Next.js
Tailwind
animation libraries
graphics dependencies committed solely for this lane
GitHub Actions solely for artwork generation
```

The organization-profile repository does not need to become a web application.

Temporary uncommitted render tooling is allowed.

A temporary script may be committed **only** if it is clearly useful for future maintainability and does not introduce runtime/package sprawl.

Default:

```text
do not commit rendering tooling
```

---

# 25. EXECUTION SEQUENCE

## Phase 0 — Preflight

Verify exact authority state.

Capture:

```text
current main SHA
current branch SHA
git status / repository mutation state where available
current rendered profile screenshot if browser access exists
```

Do not mutate product files until authority passes.

## Phase 1 — Study the portfolio source

Inspect:

```text
Kirch-Nairu/kirch-webportfolio
feature/premium-portfolio-site@eb8e4e470014a6e818f74a255ddf7b5fb8e111c9

app/layout.tsx
app/globals.css
public/images/kirich.jpg
```

Explicitly note:

```text
font pair
palette
hero proportions
portrait treatment
paper-section treatment
section index style
spacing character
line/border restraint
```

Do not begin design from memory.

## Phase 2 — Acquire legitimate portraits

Kirch:

```text
public/images/kirich.jpg
```

Jane:

```text
current Kirion-Jane GitHub avatar
```

Store Jane locally.

No generated substitutes.

## Phase 3 — Hero first

Produce desktop/mobile hero assets.

Update README enough to render hero.

Inspect actual GitHub rendering if possible.

Do **not** build Jane/method first.

The hero defines the lane.

If the hero still reads as:

```text
cybersecurity wallpaper
AI startup
hacker collective
terminal brand
```

rework before continuing.

## Phase 4 — Smithy thesis

Add the concise native section.

Verify the dark hero → warm-paper editorial mental transition still reads even though GitHub README cannot reproduce the website's full section backgrounds.

Use whitespace and imagery rather than Markdown gimmicks.

## Phase 5 — Jane profile

Create Jane desktop/mobile editorial assets.

Add native identity/link fallback.

Inspect at mobile width.

Do not proceed if Jane looks like a tiny staff-directory afterthought.

## Phase 6 — Method

Delete the old animated loop from the profile.

Implement the static typographic sequence.

Only add a method canvas if native presentation is genuinely inferior.

## Phase 7 — Cleanup

Remove obsolete neon assets after all references are gone.

Remove dead copy.

Check image filenames.

Check links.

Check alt text.

Check spelling.

## Phase 8 — GitHub render review

Inspect actual rendered branch README where possible.

Review both GitHub appearances if available:

```text
light
dark
```

Check:

```text
1440
1280
768
390
360
```

Do not treat raw Markdown source inspection as runtime rendering evidence.

## Phase 9 — Final validation

Only after visual work converges, run textual/repository checks and return evidence.

---

# 26. COMMIT STRATEGY

Use a small number of coherent commits.

Preferred:

```text
1.
KIRCH-FORGE-SMITHY-EDITORIAL-HERO

2.
KIRCH-FORGE-SMITHY-KIRIONS-PROFILE

3.
KIRCH-FORGE-SMITHY-PROFILE-INTEGRATION
```

The final integration commit may include:

```text
Smithy thesis
method
footer
README cleanup
responsive fixes
accessibility fixes
obsolete asset deletion
```

Do not manufacture commits to hit the count.

No empty commits.

No whitespace-padding commits.

---

# 27. VALIDATION

Required source validation:

```text
git diff --check
```

or connector-equivalent evidence if execution does not expose a local Git CLI.

Verify no active references remain to:

```text
smithy-header.svg
engineering-loop.svg
```

Verify all final image references resolve.

Verify Jane profile link resolves.

Verify no external portrait link is required at runtime if Jane was localized.

Verify `main` remains unchanged.

## Runtime / visual evidence

Report only what was actually observed:

```text
PASS
FAIL
NOT OBSERVED
SOURCE INSPECTED
```

Never promote source inspection into browser evidence.

---

# 28. VISUAL ACCEPTANCE — THREE-SECOND TEST

Without reading paragraphs, the profile must communicate:

```text
[ ] Kirion Smithy is an engineering organization
[ ] it belongs to the same visual world as Kirch's portfolio
[ ] a real human orchestrates it
[ ] a real Kirion is visibly part of it
[ ] it values structure and evidence
[ ] it is not a cyberpunk / hacker / AI-agent brand
```

If any of the last three fail:

```text
REWORK
```

---

# 29. HERO ACCEPTANCE

```text
[ ] actual Kirch photograph
[ ] no ASCII
[ ] no code texture
[ ] no glow
[ ] no cyber grid
[ ] no animation
[ ] title dominates
[ ] Manrope-led visual character
[ ] Instrument Serif used selectively
[ ] accent restrained
[ ] support copy concise
[ ] mobile text remains legible
[ ] image remains strong in GitHub rendering
```

---

# 30. SMITHY THESIS ACCEPTANCE

```text
[ ] section label = 01 — THE SMITHY
[ ] "Structure before spectacle." visible
[ ] "Evidence before confidence." visible
[ ] body remains concise
[ ] no marketing filler
[ ] no generic AI copy
[ ] whitespace carries hierarchy
```

---

# 31. JANE ACCEPTANCE

```text
[ ] Jane has an actual legitimate photograph
[ ] Jane's full name is visible
[ ] "The first Kirion." remains
[ ] @Kirion-Jane remains
[ ] GitHub profile is clickable
[ ] native fallback identity exists
[ ] no invented biography
[ ] no invented job title
[ ] no invented specialty
[ ] no generated portrait
[ ] desktop composition feels substantial
[ ] mobile composition remains readable
```

Governing Jane rule:

> **If the README says a real person is a Kirion, the profile must let the viewer actually see that person.**

---

# 32. METHOD ACCEPTANCE

```text
[ ] current animated engineering-loop concept is gone
[ ] sequence remains:
    Understand
    Plan
    Build
    Verify
    Deploy
    Operate
    Learn
[ ] Return principle remains
[ ] no glow
[ ] no animation
[ ] no HUD
[ ] no fake dashboard
[ ] no over-designed engineering infographic
[ ] sequence understood in one glance
```

---

# 33. OVERALL IDENTITY ACCEPTANCE

```text
[ ] ink / warm paper dominate
[ ] accent remains <10% visual weight
[ ] portraits feel editorial
[ ] typography feels portfolio-related
[ ] no neon appearance
[ ] no generic AI landing-page appearance
[ ] no hacker aesthetic
[ ] no card carnival
[ ] no badge wall
[ ] no fake metrics
[ ] README remains relatively compact
[ ] GitHub native organization page can continue naturally below it
```

---

# 34. FROZEN / PROHIBITED SURFACES

Do not touch:

```text
other Kirion organizations
product repositories
Kirion Forge repositories
Cognition repositories
Breakout repositories

GitHub Projects
Teams
People
organization membership
organization permissions
repository permissions
branch protection
workflows
secrets

issues
pull requests

Kirch portfolio source repository
```

This lane is strictly:

```text
The-Kirion-Smithy/.github
profile presentation
```

---

# 35. STOP CONDITIONS

Immediately stop and return to Maintainer if:

```text
main moved from d47b65dadc45cb3a8fbbe46c9fe3b3d193bf9ed8

unexpected product drift exists on the execution branch

Jane's legitimate portrait cannot be acquired

GitHub sanitization prevents a usable accessible presentation

a design requirement appears to require organization-setting mutation

a product repository would need mutation

a new committed frontend runtime/toolchain becomes necessary

the only way to continue appears to be AI-generating a human portrait
```

Do not silently widen the lane.

---

# 36. REQUIRED RETURN CONTRACT

Return exactly this structure:

```text
KIRION FORGE: CODE WRITER — S01 RETURN

SOURCE REPOSITORY
The-Kirion-Smithy/.github

PRODUCT BASE SHA
d47b65dadc45cb3a8fbbe46c9fe3b3d193bf9ed8

EXECUTION BRANCH
KIRION-FORGE-S01-SMITHY-EDITORIAL-REWORK

START SHA
<exact branch SHA before product mutation>

FINAL SHA
<exact final SHA>

MAIN SHA
<exact verified main SHA>


COMMITS
<list>


FILES ADDED
<list>

FILES MODIFIED
<list>

FILES REMOVED
<list>


PORTFOLIO SOURCE STUDIED
PASS / FAIL

PORTFOLIO AUTHORITY
Kirch-Nairu/kirch-webportfolio
feature/premium-portfolio-site
@eb8e4e470014a6e818f74a255ddf7b5fb8e111c9


KIRCH PORTRAIT
source:
result:

JANE PORTRAIT
source:
result:


HERO
PASS / FAIL

THE SMITHY SECTION
PASS / FAIL

JANE PROFILE
PASS / FAIL

METHOD
PASS / FAIL

FOOTER
PASS / FAIL


OLD NEON HERO REMOVED
PASS / FAIL

OLD ANIMATED LOOP REMOVED
PASS / FAIL

NO ACTIVE ASCII PRESENTATION
PASS / FAIL

NO ACTIVE NEON / GLOW PRESENTATION
PASS / FAIL


IMAGE LINKS
PASS / FAIL

JANE PROFILE LINK
PASS / FAIL

ALT TEXT
PASS / FAIL


GITHUB LIGHT
PASS / FAIL / NOT OBSERVED

GITHUB DARK
PASS / FAIL / NOT OBSERVED

1440
PASS / FAIL / NOT OBSERVED

1280
PASS / FAIL / NOT OBSERVED

768
PASS / FAIL / NOT OBSERVED

390
PASS / FAIL / NOT OBSERVED

360
PASS / FAIL / NOT OBSERVED


GIT DIFF CHECK
PASS / FAIL / NOT RUN

REMAINING VISUAL FINDINGS
NONE / exact list


EXPLICIT CONFIRMATION

main mutation
NONE

organization configuration mutation
NONE

product repository mutation
NONE

portfolio repository mutation
NONE

workflow mutation
NONE

generated human portrait
NONE

new runtime/toolchain
NONE

merge
NONE

promotion
NONE

deployment
NONE

reset
NONE

rebase
NONE

force push
NONE


FINAL DISPOSITION

SOURCE-READY FOR HUMAN VISUAL REVIEW

or

REWORK REQUIRED
```

Then stop.

Do not merge.

Do not promote.

Do not change `main`.

---

# 37. FINAL GOVERNING RULES

> **The Smithy should look like the engineering institution behind Kirch's portfolio, not like a hacker-themed AI demo.**

> **Structure before spectacle. Evidence before confidence.**

> **If the README says a real person is a Kirion, the profile should let the viewer actually see that person.**

Execute only this bounded lane and stop at candidate handoff.
