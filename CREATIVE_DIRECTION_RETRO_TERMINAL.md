# CREATIVE DIRECTION: RETRO TERMINAL / HACKER AESTHETIC
## "MAINFRAME" -- A World-Class Developer Portfolio

> "The best interface is the one that disappears. But what if the interface itself IS the art?"

---

## TABLE OF CONTENTS

1. [Philosophy & Vision](#1-philosophy--vision)
2. [Visual Identity](#2-visual-identity)
3. [Color Palettes (3 Options)](#3-color-palettes)
4. [Typography System](#4-typography-system)
5. [Layout Concepts](#5-layout-concepts)
6. [Interactive Elements](#6-interactive-elements)
7. [Unique Features](#7-unique-features)
8. [Hero Section / Boot Sequence](#8-hero-section--boot-sequence)
9. [Easter Eggs](#9-easter-eggs)
10. [Page-by-Page Breakdown](#10-page-by-page-breakdown)
11. [Technical Architecture](#11-technical-architecture)
12. [Why This Direction Wins](#12-why-this-direction-wins)
13. [Self-Rating](#13-self-rating)

---

## 1. PHILOSOPHY & VISION

### The Core Idea

This is NOT another "green text on black background" gimmick. This is a **love letter to computing itself** -- the machines that made us who we are. It says: "I don't just write code. I understand WHERE code comes from."

The aesthetic draws from:
- IBM mainframes of the 1970s-80s
- DEC VT100 terminals
- Early Unix workstations
- The amber glow of Hercules monitors
- NASA mission control interfaces
- The raw poetry of a blinking cursor

But it is executed with the precision of a 2026 design system. Every pixel is deliberate. Every animation is buttery smooth. The retro skin wraps a bleeding-edge technical core.

### The Narrative

The portfolio tells a story: **booting up a system that IS the developer**. Each section is a "program" or "process." The visitor is not just reading a resume -- they are *interfacing* with a living system. This transforms passive browsing into active exploration.

### Why Retro Terminal for a Walmart Developer?

Walmart is the world's largest company by revenue. Its tech operation runs one of the most massive distributed systems on Earth. This portfolio says: "I operate at mainframe scale. I think in systems. I respect the machines." It bridges Walmart's enterprise engineering culture with creative technical expression.

---

## 2. VISUAL IDENTITY

### Design Principles

1. **Monospace is the Melody** -- Every character occupies equal space. This creates a grid-like rhythm that is inherently beautiful and orderly.
2. **Darkness is Depth** -- Deep, near-black backgrounds create focus. Content glows. Nothing competes.
3. **Glow, Don't Glare** -- Phosphor effects are subtle. Text has a soft luminance, never a harsh neon blast. Think "warm CRT in a dark room," not "rave flyer."
4. **Texture Tells History** -- Scanlines, subtle noise, and CRT curvature effects whisper "this screen has seen things." But they never impede readability.
5. **Motion is Meaning** -- Every animation has purpose. Typing effects convey "processing." Glitch effects signal transitions. Cursor blinks signal "ready."

### Visual Elements Toolkit

| Element | Treatment | Purpose |
|---|---|---|
| **Scanlines** | CSS linear-gradient overlay, 1-2px, ~3-5% opacity | CRT authenticity without readability loss |
| **Screen Glow** | box-shadow with color spread, subtle | Phosphor warmth, depth |
| **Cursor** | Block cursor, steady blink at 1Hz | "System ready" -- the universal prompt |
| **Borders** | ASCII box-drawing characters or 1px solid lines | Terminal window framing |
| **Noise Texture** | SVG filter, <2% opacity, animated | Analog warmth |
| **CRT Curvature** | Subtle border-radius + perspective transform on hero only | Nostalgic framing device |
| **Glitch Effect** | CSS clip-path + color channel offset, on hover/transition ONLY | Controlled chaos, never random |
| **Progress Bars** | ASCII: [=========>    ] 67% | Loading states, skill levels |
| **Dividers** | Repeated dash/equals characters: ════════════ | Section breaks |

### What We Avoid

- Matrix-style falling characters (overdone, cheesy)
- Skull ASCII art or "hacking" cliches
- Neon rainbow colors
- Excessive animation that causes motion sickness
- Anything that sacrifices readability for aesthetics
- Green-on-black EVERYWHERE with no contrast variation

---

## 3. COLOR PALETTES

### PALETTE A: "PHOSPHOR" (Classic Green Terminal -- Elevated)

The iconic green-on-black, but with a warm analog soul. Not the flat #00FF00 everyone uses -- these are authentic phosphor tones with depth.

```
BACKGROUND
  --bg-deep:        #0A0E0A    (near-black with green undertone)
  --bg-surface:     #0D120D    (slightly elevated surfaces)
  --bg-panel:       #111A11    (cards, modals)

FOREGROUND (The Phosphor Greens)
  --text-primary:   #33FF66    (P1 phosphor green -- bright, for headings)
  --text-body:      #2BCC52    (softer green -- for body text, easier on eyes)
  --text-dim:       #1A7A33    (dimmed text, comments, secondary info)
  --text-ghost:     #0D3D1A    (barely visible -- decorative, line numbers)

ACCENTS
  --accent-warm:    #FFB000    (amber -- for warnings, highlights, links)
  --accent-cyan:    #00CED1    (cool accent -- for special callouts)
  --accent-error:   #FF3333    (error/alert red)

GLOW
  --glow-green:     rgba(51, 255, 102, 0.15)   (text-shadow, box-shadow)
  --glow-amber:     rgba(255, 176, 0, 0.12)     (warm glow for accents)

UTILITY
  --border:         #1A3D1A    (subtle green borders)
  --selection-bg:   #33FF6633  (text selection highlight)
```

**Mood:** Underground. Serious. The developer who SSH'd into their first server at 14 and never looked back.

---

### PALETTE B: "AMBER MAINFRAME" (Warm, Analog, Distinguished)

Inspired by Hercules amber monitors and early banking/financial terminals. This palette is WARM, approachable, and deeply unique in the developer portfolio space.

```
BACKGROUND
  --bg-deep:        #0C0A06    (near-black with warm brown undertone)
  --bg-surface:     #12100A    (warm dark surface)
  --bg-panel:       #1A1610    (cards, modals -- like aged paper in shadow)

FOREGROUND (The Amber Phosphors)
  --text-primary:   #FFB000    (classic amber -- headings, commands)
  --text-body:      #CC8E00    (softer amber -- body text)
  --text-dim:       #7A5500    (dimmed amber -- secondary info)
  --text-ghost:     #3D2B00    (decorative, line numbers)

ACCENTS
  --accent-cream:   #FFE0A0    (warm highlight -- almost white in this context)
  --accent-blue:    #4A90D9    (cool contrast accent -- links, special elements)
  --accent-error:   #FF4444    (error red, slightly warm)

GLOW
  --glow-amber:     rgba(255, 176, 0, 0.12)    (primary glow)
  --glow-cream:     rgba(255, 224, 160, 0.08)   (subtle warm bloom)

UTILITY
  --border:         #3D2B00    (amber-tinted borders)
  --selection-bg:   #FFB00033  (amber text selection)
```

**Mood:** Institutional. Authoritative. The mainframe operator who kept the bank running at 3 AM. Sophisticated and rare -- almost nobody uses amber for portfolios.

---

### PALETTE C: "IBM BLUE STEEL" (Corporate Retro -- The Power Play)

Inspired by IBM 3270 mainframe terminals, blue-tinted CRTs, and the steel-gray aesthetic of 1980s computing infrastructure. This one bridges retro and corporate in a way that would make a Walmart hiring manager lean forward.

```
BACKGROUND
  --bg-deep:        #080B12    (deep blue-black, like a powered-down screen)
  --bg-surface:     #0C1019    (elevated surface with blue cast)
  --bg-panel:       #111825    (panels, cards)

FOREGROUND (The Blue Phosphors)
  --text-primary:   #7EB8DA    (IBM terminal blue -- headings)
  --text-body:      #5A9BBF    (softer blue -- body text)
  --text-dim:       #3A6B8A    (dimmed blue -- secondary)
  --text-ghost:     #1E3A4D    (decorative elements)

ACCENTS
  --accent-white:   #C8D8E8    (near-white with blue tint -- high emphasis)
  --accent-amber:   #FFB000    (warm contrast -- highlights, warnings)
  --accent-green:   #33CC66    (success/active states)
  --accent-error:   #E84855    (error red)

GLOW
  --glow-blue:      rgba(126, 184, 218, 0.12)   (cool phosphor glow)
  --glow-amber:     rgba(255, 176, 0, 0.08)      (warm accent glow)

UTILITY
  --border:         #1E3A4D    (blue-gray borders)
  --selection-bg:   #7EB8DA33  (blue text selection)
```

**Mood:** Corporate power. Enterprise scale. The developer who architects systems that handle millions of transactions. This says "I belong in the room where decisions are made" while still being unmistakably retro-tech.

---

### RECOMMENDED PALETTE

**Palette B ("Amber Mainframe") as the PRIMARY direction**, with the option to let users toggle between all three as a "theme" feature. Here is why:

1. **Uniqueness** -- Everyone does green terminal. Almost nobody does amber. Instant differentiation.
2. **Warmth** -- Amber is psychologically warm and inviting. It says "I'm approachable" while still looking technical.
3. **Ergonomics** -- Amber monitors were literally designed to reduce eye strain. Your portfolio will be comfortable to read.
4. **Walmart Alignment** -- Amber (#FFB000) has a natural harmonic relationship with Walmart's Spark Yellow (#FFC220). This is a subtle but powerful subconscious signal.
5. **Sophistication** -- It reads as "vintage luxury" rather than "hacker cliche."

---

## 4. TYPOGRAPHY SYSTEM

### OPTION A: "The Purist" -- JetBrains Mono + Inter

```
PRIMARY (Headings, Commands, Code):
  Font: JetBrains Mono
  Source: Google Fonts (free)
  Weights: 400 (Regular), 700 (Bold)
  Features: Coding ligatures enabled
  Why: The gold standard of modern monospace. Clean, tall x-height,
       excellent ligatures (=> becomes a proper arrow). Says "I code
       professionally."

SECONDARY (Body Text, Descriptions):
  Font: Inter
  Source: Google Fonts (free)
  Weights: 300, 400, 500
  Why: The most readable sans-serif on screens. Provides visual relief
       from monospace density. Variable font = one file, all weights.

ACCENT (Terminal Prompts, ASCII Art):
  Font: IBM Plex Mono
  Source: Google Fonts (free)
  Weights: 400, 600
  Why: Literal IBM DNA. Pairs beautifully with JetBrains Mono while
       being distinct enough to signal "system message" vs "user input."
```

### OPTION B: "The Character" -- Space Mono + Space Grotesk

```
PRIMARY (Everything Terminal):
  Font: Space Mono
  Source: Google Fonts (free)
  Weights: 400, 700
  Why: Inspired by 1960s space-age technology and headline typography.
       Has personality and quirk that JetBrains Mono lacks. The
       letterforms feel like they belong on a NASA mission control screen.

SECONDARY (Body, Descriptions):
  Font: Space Grotesk
  Source: Google Fonts (free)
  Weights: 300-700 (variable)
  Why: The proportional sibling of Space Mono. Same DNA, same era,
       but optimized for reading paragraphs. The pairing is seamless.

ACCENT (Decorative, ASCII):
  Font: VT323
  Source: Google Fonts (free)
  Weight: 400 only
  Why: Pixel-perfect retro terminal font. Use sparingly -- for boot
       sequence text, loading messages, or decorative elements. Gives
       authentic 8-bit flavor without compromising the primary system.
```

### OPTION C: "The Minimalist" -- Fira Code + Fira Sans

```
PRIMARY (Code, Headings):
  Font: Fira Code
  Source: Google Fonts (free)
  Weights: 300-700 (variable)
  Features: Full ligature support
  Why: Mozilla's contribution to monospace excellence. Slightly more
       compact than JetBrains Mono. The ligatures are beautiful.
       Variable font means smooth weight transitions for emphasis.

SECONDARY (Body):
  Font: Fira Sans
  Source: Google Fonts (free)
  Weights: 300, 400, 500
  Why: Same family, same rhythm, proportional. The transition from
       mono to sans feels natural and intentional.

ACCENT (System Messages):
  Font: Source Code Pro
  Source: Google Fonts (free)
  Weights: 400, 600
  Why: Adobe's monospace workhorse. Slightly different character than
       Fira Code -- use it for "system" messages while Fira Code is
       "user" text. Creates a subtle two-voice dialogue.
```

### RECOMMENDED TYPOGRAPHY

**Option B (Space Mono + Space Grotesk + VT323)** -- It has the most personality. Space Mono's 1960s character makes every line of text feel like it belongs in a control room. The VT323 accent font adds authentic retro flavor for special moments. This combination is distinctive without sacrificing readability.

### Type Scale

```
--text-xs:    0.75rem   (12px)  -- line numbers, timestamps
--text-sm:    0.875rem  (14px)  -- secondary info, captions
--text-base:  1rem      (16px)  -- body text
--text-lg:    1.125rem  (18px)  -- emphasized body
--text-xl:    1.25rem   (20px)  -- sub-headings
--text-2xl:   1.5rem    (24px)  -- section headings
--text-3xl:   2rem      (32px)  -- page titles
--text-4xl:   2.5rem    (40px)  -- hero text (boot sequence)
--text-hero:  3.5rem    (56px)  -- main name/title (used once)

Line Height: 1.6 for body, 1.2 for headings
Letter Spacing: +0.05em for monospace headings (breathe)
```

---

## 5. LAYOUT CONCEPTS

### The "Dual Mode" Architecture

The portfolio operates in TWO modes that users can switch between:

#### MODE 1: "TERMINAL" (Default on Desktop)

The entire site is presented as a terminal emulator window. Navigation is done by typing commands OR clicking command suggestions. Content loads in as if being "printed" to the terminal.

```
+----------------------------------------------------------+
| MAINFRAME v2.1.0 - anshull@walmart-dev                   |
| [File] [View] [Session] [Help]              [_][#][X]    |
+----------------------------------------------------------+
|                                                           |
| Last login: Mon Feb  8 09:14:22 2026                      |
| System: PORTFOLIO_OS v2.1 (arm64-darwin-25.2.0)           |
|                                                           |
| > whoami                                                  |
|                                                           |
| ANSHULL GARG                                              |
| Software Developer @ Walmart                              |
| ------------------------------------------------         |
| Building systems that serve millions.                     |
|                                                           |
| > help                                                    |
|                                                           |
| Available commands:                                       |
|   about      - Who I am and what I do                     |
|   skills     - Technical competencies                     |
|   experience - Work history & achievements                |
|   projects   - Things I've built                          |
|   contact    - Get in touch                               |
|   resume     - Download my resume                         |
|   theme      - Toggle color scheme [green|amber|blue]     |
|   clear      - Clear the terminal                         |
|   sudo hire me - ???                                      |
|                                                           |
| > _                                                       |
+----------------------------------------------------------+
```

#### MODE 2: "GUI" (Default on Mobile, Toggle on Desktop)

A more traditional scrollable layout, but still terminal-THEMED. Sections are presented as "windows" or "panes" with terminal chrome (title bars, minimize/maximize buttons). The aesthetic is maintained but navigation is conventional.

This dual approach solves the biggest problem with terminal portfolios: **recruiters who don't want to type commands.** They get the visual impact without the interaction barrier.

### Layout Grid

```
Desktop:  12-column grid, max-width 1200px, 24px gutters
Tablet:   8-column grid, max-width 768px, 16px gutters
Mobile:   4-column grid, full-width, 16px gutters

Terminal mode: single-column, max-width 80ch (true terminal width)
GUI mode:      responsive multi-column with terminal-styled panels
```

### Section Layout Patterns

**"Single Pane"** -- Full-width terminal output for text-heavy sections (About, Experience)

**"Split Pane"** -- Side-by-side terminal windows for comparisons or code + description layouts

**"Tiled"** -- Multiple small terminal windows arranged in a grid (Projects, Skills)

**"Full Bleed"** -- Breaks out of the terminal frame for high-impact moments (Hero, Contact CTA)

---

## 6. INTERACTIVE ELEMENTS

### 6.1 The Command Line Interface

The crown jewel. A fully functional command-line interface where visitors can type real commands.

**Core Commands:**
```
whoami          -> Displays name, title, and one-liner bio
about           -> Full bio with typing animation
skills          -> Animated skill bars rendered in ASCII
experience      -> Work history in structured format
projects        -> List of projects with descriptions
project [name]  -> Deep dive into a specific project
contact         -> Contact info and links
resume          -> Triggers PDF download
theme [name]    -> Switches color palette (green/amber/blue)
clear           -> Clears terminal
help            -> Lists all commands
history         -> Shows command history
date            -> Current date/time
echo [text]     -> Echoes text back
cat resume.txt  -> Alternative resume view
ls              -> Lists "files" (sections)
cd [section]    -> Navigate to section
pwd             -> Shows current "directory"
man [command]   -> Manual page for a command (with personality)
```

**Secret Commands (not listed in help):**
```
sudo hire me    -> Special hire animation
konami          -> Triggers konami code easter egg
matrix          -> Brief matrix rain effect (3 seconds, then stops)
coffee          -> ASCII coffee cup animation
fortune         -> Random programming quote
cowsay [text]   -> Classic cowsay output
ping google.com -> Fake ping with fun messages
rm -rf /        -> "Nice try." message
git blame       -> Humorous blame output
neofetch        -> System info styled display
```

### 6.2 Typing Animations

All "output" text appears with a typing effect:
- **Speed:** 20-40ms per character for short text, instant-reveal for long blocks (with option to skip)
- **Sound:** Optional subtle keyclick sounds (muted by default, toggle in settings)
- **Cursor:** Block cursor (not line) that blinks at exactly 1Hz during pauses
- **Skip:** Clicking anywhere or pressing any key instantly reveals all text (critical for UX)

### 6.3 Boot Sequence (See Section 8)

### 6.4 Navigation Suggestions

After each command output, contextual "breadcrumbs" appear:

```
> about

[Full bio text appears...]

Try: skills | experience | projects | contact
> _
```

These are CLICKABLE -- solving the discoverability problem.

### 6.5 Tab Completion

Pressing Tab auto-completes commands. Pressing Tab twice shows all options. This small detail separates a toy from a real terminal experience.

### 6.6 Command History

Up/Down arrows cycle through previously entered commands. Just like a real terminal.

### 6.7 Interactive Skill Visualization

```
> skills

LANGUAGES
  JavaScript  [===================>   ] 92%  *** 8 years
  TypeScript  [=================>     ] 85%  *** 5 years
  Python      [================>      ] 80%  *** 6 years
  Java        [===============>       ] 75%  *** 4 years
  Go          [===========>           ] 55%  *** 2 years

FRAMEWORKS
  React       [===================>   ] 92%
  Node.js     [=================>     ] 88%
  Next.js     [================>      ] 82%

TOOLS & PLATFORMS
  AWS         [=================>     ] 85%
  Docker      [================>      ] 80%
  Kubernetes  [============>          ] 60%
  CI/CD       [==================>    ] 90%

[Bars animate in sequentially, left to right]
```

### 6.8 Scroll Indicators

In GUI mode, sections have terminal-style scroll indicators:

```
--- MORE --- (Press SPACE or scroll to continue)
```

---

## 7. UNIQUE FEATURES

### 7.1 "System Monitor" -- Live Activity Dashboard

A persistent subtle element (maybe in a corner or footer) showing "system stats" that are actually portfolio analytics:

```
SYSTEM STATUS                          UPTIME: 847d 14h 22m
CPU: ||||||||..  78%  (visitors today)
MEM: ||||||....  62%  (sections explored)
NET: |||||||||.  91%  (avg. engagement)
PID   PROCESS           CPU   MEM
1     portfolio.exe      2.1%  128MB
47    animation.worker   0.8%   64MB
```

This is purely decorative/fun but adds incredible depth to the illusion.

### 7.2 "Multi-Window" Desktop Mode

Inspired by Kielx's terminal portfolio with WinBox.js -- projects can be opened as draggable, resizable, minimizable terminal windows that float on the screen. Users can arrange them like a real desktop environment. This is the "holy grail" feature that elevates the portfolio from terminal gimmick to genuine interactive experience.

### 7.3 Theme Persistence & Customization

The `theme` command doesn't just swap colors -- it changes the entire CRT effect:
- **Green:** P1 phosphor glow, sharper scanlines, cooler tone
- **Amber:** P3 phosphor glow, softer edges, warmer tone, slight vignette
- **Blue:** IBM-style flat blue, minimal glow, professional

Theme preference is saved to localStorage so returning visitors see their choice.

### 7.4 "Commit History" Timeline

The Experience section is presented as a `git log`:

```
> git log --oneline --graph

* e8f2a1c (HEAD -> main) Senior Software Developer @ Walmart (2024-Present)
|   - Architected microservices handling 2M+ requests/day
|   - Led team of 5 engineers on checkout optimization
|   - Reduced API latency by 40% through caching strategy
|
* b4d7e9a Software Developer @ Walmart (2022-2024)
|   - Built React component library used across 12 teams
|   - Implemented CI/CD pipeline reducing deploy time by 60%
|
* 1a3c5f7 Software Engineering Intern @ [Company] (2021-2022)
|   - Developed internal tooling for data pipeline monitoring
|
* 0000001 (tag: v1.0) init: Born, started breaking things
```

This reframes a resume as a development history. It speaks DIRECTLY to developers and technical hiring managers in their own language.

### 7.5 "File System" Navigation

The portfolio has a virtual file system:

```
/home/anshull/
  /about/
    bio.txt
    philosophy.md
  /experience/
    walmart-senior.md
    walmart-dev.md
  /projects/
    project-alpha/
      README.md
      demo.link
    project-beta/
      README.md
  /skills/
    languages.json
    frameworks.json
    tools.json
  /contact/
    email.txt
    links.json
  resume.pdf
  .secret/
    easter-eggs.sh
```

Users can `ls`, `cd`, `cat` through the file system. This is the interactive storytelling layer.

### 7.6 Visitor "Session" Concept

Each visit is a "session." The terminal greets returning visitors differently:

**First visit:**
```
Welcome to MAINFRAME v2.1.0
Establishing new session...
Session ID: #a7f2e1
Type 'help' to get started.
```

**Return visit:**
```
Welcome back.
Last session: 3 days ago
You explored: about, skills, projects
Suggestion: Try 'experience' or 'contact' next.
```

This is stored in localStorage and creates a sense of continuity and personalization.

### 7.7 "Man Pages" with Personality

The `man` command returns manual pages with humor:

```
> man about

ABOUT(1)                    MAINFRAME Manual                    ABOUT(1)

NAME
    about - display information about the system operator

SYNOPSIS
    about [--verbose] [--tldr]

DESCRIPTION
    Displays biographical information about Anshull Garg,
    including origin story, current role, and what happens
    when you give a curious kid access to a computer.

OPTIONS
    --verbose    The long version. Grab coffee.
    --tldr       Just the highlights.

SEE ALSO
    skills(1), experience(1), contact(1)

BUGS
    Sometimes talks about distributed systems at parties.
```

### 7.8 Accessibility Toggle

A critical feature: `a11y` command or a visible toggle that:
- Disables all animations and glitch effects
- Removes scanline overlays
- Increases contrast ratios
- Switches to the GUI mode
- Respects `prefers-reduced-motion`

This shows technical maturity and empathy -- qualities hiring managers value.

---

## 8. HERO SECTION / BOOT SEQUENCE

### The First 10 Seconds -- The Most Important Part

When a visitor lands on the site, they see a **boot sequence**. This is the portfolio's handshake. It must be: fast enough to not frustrate, slow enough to create atmosphere, and skippable for returning visitors.

### The Sequence (Total: 4-6 seconds, skippable after 1 second)

```
PHASE 1 (0.0s - 0.5s): BLACK SCREEN
  Screen is completely black.
  A single block cursor appears, blinking.
  Faint CRT hum sound (if audio enabled).

PHASE 2 (0.5s - 1.5s): BIOS/POST
  Text appears rapidly (not typed, but rendered line-by-line):

  MAINFRAME BIOS v2.1.0
  Copyright (c) 2026 Anshull Garg Systems

  Checking memory.......... 16384 MB OK
  Detecting drives......... SSD-PORTFOLIO [256GB]
  Loading kernel........... CREATIVE_OS 6.1.0-arm64
  Initializing display..... [OK]

  [A subtle "click" on the screen as if a CRT warming up]
  [Screen briefly flickers -- very subtle, one frame]

PHASE 3 (1.5s - 2.5s): SYSTEM INIT
  Starting services:
    [OK] network.service
    [OK] creativity.daemon
    [OK] portfolio.engine
    [OK] coffee.intake.monitor

  All systems operational.

PHASE 4 (2.5s - 3.5s): LOGIN

  MAINFRAME login: anshull
  Password: ********

  Last login: [actual current date/time]
  Welcome to MAINFRAME -- Anshull Garg's Portfolio

PHASE 5 (3.5s - 5.0s): THE REVEAL

  The terminal "window" scales up slightly.
  CRT curvature effect activates.
  Scanlines fade in.
  The prompt appears:

  > _

  After a 0.5s pause, the auto-typed welcome message begins:

  > whoami

  ╔══════════════════════════════════════════════════╗
  ║                                                  ║
  ║   ANSHULL GARG                                   ║
  ║   Software Developer @ Walmart                   ║
  ║                                                  ║
  ║   I build systems that serve millions.            ║
  ║   I care about performance, reliability,          ║
  ║   and the craft of engineering.                   ║
  ║                                                  ║
  ╚══════════════════════════════════════════════════╝

  Type 'help' to explore. Click anywhere to navigate.

  > _
```

### Skip Behavior

- After 1 second, a subtle "Press any key to skip..." appears in dim text
- Clicking, pressing any key, or scrolling instantly completes the boot
- Returning visitors (localStorage check) get an abbreviated 1-second version
- The boot can be entirely disabled in accessibility mode

### Mobile Adaptation

On mobile, the boot sequence is shortened to 2 seconds. The terminal window is full-screen. The blinking cursor is larger. Touch-friendly command suggestions replace the input field.

---

## 9. EASTER EGGS

### 9.1 The Konami Code

Entering Up, Up, Down, Down, Left, Right, Left, Right, B, A triggers:

The entire screen glitches dramatically for 0.5 seconds, then a retro 8-bit version of the portfolio loads -- pixel art avatar, chiptune background music (muted by default), and NES-style color palette. A "PLAYER 1 START" title screen. After 5 seconds or a keypress, it fades back to normal with the message:

```
ACHIEVEMENT UNLOCKED: "Old School"
You found the secret. You're clearly one of us.
```

### 9.2 `sudo hire me`

```
> sudo hire me

[sudo] password for visitor: ********
Verifying credentials...
Checking references...
Analyzing cultural fit...
Running background check on your good taste in portfolios...

ACCESS GRANTED.

Congratulations. You have been granted Level 5 clearance.
Opening secure channel to anshull@contact...

[Contact form slides into view with a pre-filled subject line:
"I found the sudo command -- let's talk"]
```

### 9.3 `rm -rf /`

```
> rm -rf /

rm: cannot remove '/': Permission denied
Nice try. This system has better security than that.

(But seriously, I do take security seriously. Ask me about
my approach to secure coding practices.)
```

### 9.4 `coffee`

An ASCII art coffee cup that "fills up" with an animation:

```
> coffee

Brewing...

        ) )  )
       ( ( (
     ........
     |      |]
     \      /
      `----'

    COFFEE READY
    Fuel level: [==========] 100%

    Fun fact: This portfolio was mass produced on mass coffee.
```

### 9.5 `neofetch`

```
> neofetch

        .---.         anshull@mainframe
       /     \        -----------------
      |  O O  |       OS: PORTFOLIO_OS 2.1.0 arm64
      |  \_/  |       Host: The Internet
       \ ___ /        Kernel: Next.js 15.x
    ___/     \___     Shell: custom-terminal 1.0
   |             |    Resolution: Responsive
   |  ANSHULL G  |    Theme: Amber Mainframe
   |_____________|    Terminal: MAINFRAME v2.1
                      CPU: Caffeine-Powered Brain
   [ASCII portrait    GPU: Creative Vision 3080
    or simple icon]   Memory: Many Tabs Open
                      Uptime: [age] years
                      Languages: JS, TS, Python, Java
                      Current Quest: Building the future
```

### 9.6 Hidden `.secret` Directory

```
> cd .secret
> ls

total 3
-rw-r--r-- 1 anshull dev  easter-eggs.sh
-rw-r--r-- 1 anshull dev  fun-facts.txt
-rw-r--r-- 1 anshull dev  playlist.m3u

> cat fun-facts.txt

FUN FACTS ABOUT THE DEVELOPER
==============================
1. First line of code: HTML in 2012
2. Favorite editor: VS Code (sorry, vim purists)
3. Tabs vs spaces: Spaces. Fight me.
4. Most proud bug fix: That one race condition at 2 AM
5. This portfolio has [X] lines of code
6. You are visitor #[count] to find this directory
```

### 9.7 Barrel Roll

```
> do a barrel roll
```
The entire page does a 360-degree CSS rotation (like Google's version). Brief, delightful.

### 9.8 The "Interview Question"

```
> interview

Pop quiz! What's the time complexity of finding the best
candidate for your open position?

A) O(1) -- You already found them. (Type: 'contact')
B) O(n) -- Keep looking at portfolios.
C) O(n!) -- Try every permutation. Life is short.

> _
```

### 9.9 Sound Design Toggle

```
> sound on

Ambient CRT hum activated.
Keypress sounds enabled.
You're now fully immersed. Enjoy.

> sound off

Silence is golden. All audio disabled.
```

---

## 10. PAGE-BY-PAGE BREAKDOWN

### HOME (The Terminal)
- Boot sequence (see Section 8)
- Command-line interface
- Contextual navigation suggestions
- Quick-stat display in corner

### ABOUT
```
> about

Loading personal data...

WHO I AM
--------
I'm Anshull Garg -- a software developer at Walmart who
believes great engineering is equal parts science and craft.

[Full bio, rendered with typing animation for the first
paragraph, then instant-reveal for the rest]

WHAT I BELIEVE IN
-----------------
> Clean code that the next developer will thank you for
> Systems thinking over feature thinking
> Performance is a feature, not an afterthought
> Documentation is love

CURRENTLY
---------
Role:     Software Developer @ Walmart
Location: [City]
Focus:    [Current focus area]
Status:   Open to interesting conversations
```

### EXPERIENCE (Git Log Format)
See Section 7.4. Each "commit" is expandable. Clicking a commit hash reveals full details in a diff-like format.

### PROJECTS (File Listing with Preview)
```
> ls -la projects/

total 6
drwxr-xr-x  project-alpha/    "Microservice orchestration platform"
drwxr-xr-x  project-beta/     "Real-time analytics dashboard"
drwxr-xr-x  project-gamma/    "Open-source CLI tool"
-rw-r--r--  side-project.js   "Fun weekend build"

> cat projects/project-alpha/README.md

PROJECT ALPHA
=============
[Description, tech stack, my role, impact metrics, links]

Tech: React | Node.js | AWS Lambda | DynamoDB
Role: Lead Developer
Impact: 40% reduction in API response time

[Screenshot rendered in ASCII art or as an embedded image
within a terminal-styled frame]

[DEMO] [SOURCE] [CASE STUDY]
```

### SKILLS
Interactive ASCII skill bars (see Section 6.7). Organized by category. Clickable to expand with context.

### CONTACT
```
> contact

ESTABLISHING SECURE CONNECTION...
Encryption: AES-256
Protocol: HTTPS/TLS 1.3

CONNECTION ESTABLISHED.

AVAILABLE CHANNELS
==================
  Email:    anshull@example.com     [OPEN]
  GitHub:   github.com/anshull      [OPEN]
  LinkedIn: linkedin.com/in/anshull [OPEN]
  Twitter:  @anshull                [OPEN]

Or type 'message' to send a direct transmission:

> message

TO: anshull@mainframe
SUBJECT: _
BODY: _

[Inline contact form styled as terminal input]
```

---

## 11. TECHNICAL ARCHITECTURE

### Recommended Stack

```
Framework:    Next.js 15 (App Router)
Language:     TypeScript
Styling:      Tailwind CSS v4 + CSS custom properties for theming
Animation:    Framer Motion (typing, glitch, transitions)
Terminal:     Custom React component (not a library -- full control)
State:        Zustand (lightweight, perfect for terminal state)
Font Loading: next/font (optimized, no layout shift)
Deployment:   Vercel (instant deploys, edge functions)
Analytics:    Vercel Analytics or Plausible (privacy-first)
```

### Performance Targets

```
Lighthouse Score:   95+ across all categories
First Paint:        < 0.5s (the black screen IS the first paint)
Interactive:        < 1.5s (skip button works immediately)
Bundle Size:        < 150KB initial JS
Font Loading:       Preloaded, WOFF2, subset to needed characters
CLS:                0 (monospace = predictable layout)
```

### Key Technical Decisions

1. **Custom terminal, not a library.** Libraries like jQuery Terminal are bloated and limit customization. A custom React component with Zustand state gives full control over every interaction.

2. **CSS-only CRT effects.** No canvas or WebGL for scanlines/glow. CSS pseudo-elements and gradients are GPU-accelerated and performant.

3. **Streaming text, not character-by-character DOM updates.** Use CSS `@keyframes` with `steps()` and `overflow: hidden` + `width` animation for typing effects. Falls back gracefully.

4. **Accessible from the start.** All terminal "output" is in semantic HTML (`<article>`, `<section>`, `<nav>`). The terminal input is a real `<input>` with ARIA labels. Screen readers get a perfectly structured document.

5. **Progressive enhancement.** JavaScript disabled? The site renders as a static, well-structured page with all content visible. The terminal is an enhancement, not a requirement.

---

## 12. WHY THIS DIRECTION WINS

### The Argument

There are hundreds of developer portfolios. Most fall into three traps:

1. **The "Clean Minimal" trap** -- Beautiful but forgettable. It's a white page with nice typography. It says nothing about who you are. Close the tab, forget the name.

2. **The "3D Spectacle" trap** -- WebGL spinning globes, particles, three.js showcases. Impressive for 5 seconds. Then the recruiter can't find your email. Performance tanks on their 2019 MacBook Air.

3. **The "Template" trap** -- Looks like 10,000 other portfolios because it IS the same template.

The Retro Terminal direction avoids ALL three traps:

**It's not minimal -- it's MAXIMAL in personality.** Every pixel, every interaction, every command tells the story of a developer who lives and breathes technology. Visitors don't just read about you -- they EXPERIENCE your worldview.

**It's not a spectacle -- it's a TOOL.** The terminal isn't decoration. It's a functional interface. It demonstrates real engineering: state management, command parsing, virtual file systems, responsive design, accessibility. The aesthetic IS the technical showcase.

**It can't be a template -- it's a SYSTEM.** The virtual file system, the command set, the personality in every `man` page, the git-log resume -- these are deeply personal. Nobody can clone this and swap in their name. It's as unique as a fingerprint.

### For Walmart Specifically

- **Enterprise resonance:** Walmart's tech runs on massive backend systems. A terminal aesthetic signals "I think in systems, not just screens."
- **Engineering culture:** Walmart engineering values reliability, scale, and craft. This portfolio radiates all three.
- **Differentiation:** Among hundreds of applicants with React portfolios, THIS is the one that gets forwarded in Slack with "you HAVE to see this."
- **Conversation starter:** Every Easter egg, every command, every detail is a talking point in an interview. "Tell me about the git-log experience section" is a better conversation than "walk me through your resume."

### The Emotional Impact

When a hiring manager visits this portfolio, here is what they feel:

1. **Curiosity** (0-3s): "What is this? A terminal?" The boot sequence hooks them.
2. **Delight** (3-10s): "Oh wow, I can type commands." They try `help`. They smile.
3. **Respect** (10-60s): "This person BUILT this. The tab completion works. The git log is clever." Technical admiration builds.
4. **Connection** (60s+): They find an Easter egg. They laugh. They remember the name.
5. **Action**: They click `contact`. They send the email. They forward the link.

No other aesthetic creates this emotional journey. Minimal doesn't create curiosity. 3D doesn't create connection. Only a SYSTEM you can explore creates all five.

---

## 13. SELF-RATING

| Dimension | Score | Justification |
|---|---|---|
| **Uniqueness** | 9/10 | Amber terminal palette, dual-mode UI, virtual file system, and git-log resume are all uncommon. Not a perfect 10 because terminal portfolios exist -- but none with this level of sophistication and these specific innovations. |
| **Memorability** | 10/10 | The boot sequence alone is unforgettable. The command-line interaction creates active engagement (vs. passive scrolling), which cognitive science shows dramatically improves recall. Easter eggs give visitors stories to tell: "I found this portfolio where you can type commands..." |
| **Professionalism** | 8/10 | The dual-mode (terminal + GUI) approach solves the professionalism concern. Recruiters who want a normal portfolio get one. Technical leaders who appreciate craft get the terminal. The -2 is because some very traditional hiring managers may find it "unusual" -- but for a software developer role, that's a feature, not a bug. |
| **Technical Impressiveness** | 10/10 | Building a custom terminal emulator with tab completion, command history, virtual file system, theme switching, accessibility mode, and responsive design is a portfolio-in-a-portfolio. It IS the project. Every line of code is proof of competency. |
| **Hiring Impact** | 9/10 | This portfolio gets forwarded. It gets bookmarked. It gets mentioned in interview debriefs. It shifts the conversation from "does this person meet the bar?" to "we need to talk to this person." The -1 is because hiring is ultimately about the full picture, not just the portfolio -- but this gives you the strongest possible opening. |

### COMPOSITE SCORE: 46/50

---

## APPENDIX A: MOOD BOARD REFERENCES

### Websites to Study
- Sat Naing's Terminal Portfolio (satnaing.dev) -- functional terminal, clean
- Kielx's Terminal Portfolio -- WinBox.js multi-window approach
- cool-retro-term (Linux app) -- CRT shader effects done right
- Cathode (macOS app, discontinued) -- the gold standard of CRT emulation
- Non-OS by Nilay Nishit (Awwwards) -- Windows 3.1 style, retro OS
- Poolsuite.net -- retro computing aesthetic done with extreme sophistication

### Films & Media for Tone Reference
- WarGames (1983) -- the "shall we play a game?" terminal
- Alien (1979) -- the Nostromo computer interface
- Tron: Legacy (2010) -- the Kevin Flynn terminal scenes
- Mr. Robot -- hacking scenes with real terminal accuracy
- Blade Runner 2049 -- retro-futuristic terminal interfaces

### Real Hardware to Emulate
- IBM 5151 Monitor (green phosphor P39)
- Hercules Graphics Card amber monitors
- DEC VT100 / VT220 terminals
- Apple II monochrome display
- Commodore 64 blue screen (for the blue palette)

---

## APPENDIX B: ACCESSIBILITY COMMITMENT

This portfolio will meet WCAG 2.1 AA standards:

1. **All CRT effects are cosmetic overlays** -- removing them reveals perfectly structured, high-contrast content
2. **`prefers-reduced-motion` is respected** -- no typing animations, no glitch effects, no boot sequence
3. **`prefers-color-scheme` is respected** -- an accessible light theme variant exists
4. **Keyboard navigation** -- full tab-order, focus indicators, no keyboard traps
5. **Screen reader tested** -- all terminal "output" is semantic HTML with proper headings, landmarks, and ARIA labels
6. **Color contrast** -- all palettes are tested for 4.5:1 minimum contrast ratios (body text) and 3:1 (large text)
7. **Seizure safety** -- CRT flicker is subtle (opacity changes only), never full-screen flash. Toggle to disable entirely.
8. **No audio autoplay** -- all sound is off by default, explicitly toggled

---

## APPENDIX C: IMPLEMENTATION PRIORITY

### Phase 1: Foundation (Week 1)
- Next.js project setup with TypeScript + Tailwind
- Terminal component with basic command parsing
- Amber theme implementation
- Core commands: help, about, skills, experience, projects, contact
- Responsive layout (terminal + GUI mode)

### Phase 2: Polish (Week 2)
- Boot sequence animation
- CRT effects (scanlines, glow, noise)
- Typing animations with skip functionality
- Tab completion and command history
- Theme switching (3 palettes)

### Phase 3: Delight (Week 3)
- Easter eggs implementation
- Virtual file system (`ls`, `cd`, `cat`)
- Git-log experience section
- Sound design (optional audio)
- Returning visitor detection
- Performance optimization

### Phase 4: Launch (Week 4)
- Accessibility audit and fixes
- Cross-browser testing
- Lighthouse optimization
- Content finalization
- SEO metadata
- Deploy to Vercel + custom domain

---

*This document was prepared as a creative direction proposal for Anshull Garg's developer portfolio. Every recommendation is grounded in research of current design trends, accessibility best practices, and the psychology of hiring in the tech industry.*

*The retro terminal is not nostalgia for nostalgia's sake. It is a statement: "I understand where we've been, I'm building where we're going, and I made the journey itself worth exploring."*
