# Meadow Kingdom 2: The Forgotten Realms

## Core Concept
Sequel to Meadow Kingdom. Same character creator (expanded), but a much bigger adventure with real puzzles suitable for a 10-year-old. Multiple sub-adventures (Stages), each with 3-5 levels. Mix of side-scrolling and top-down exploration levels. Single HTML5 canvas game, mobile-first.

## Target: Age 8-12 (up from 7 in original)

---

## CHARACTER CREATION (Expanded from Original)

Keep all original options, add:
- **Class choice**: Explorer (faster movement), Inventor (can build gadgets), Healer (companion abilities stronger)
- **Pet companion selector**: Fox (default Stage 1 companion), but can pick starting companion appearance
- **Name input**: Player names their character (shown in dialogue)

---

## STAGE & LEVEL STRUCTURE

### FREE STAGES (F2P)

**STAGE 1: THE WHISPERING WOODS** (5 levels)
*Companion: Fox named "Ember"*
*Goal: Save a trapped unicorn from enchanted vines*

- **1-1: The Overgrown Path** (side-scroll)
  - Long scrolling forest path with fallen logs, mushroom platforms
  - Puzzle: Arrange colored mushrooms to match a pattern shown by fireflies
  - Obstacle: Thorny vines block path — tap sequence to clear them
  - Environmental: Day/night cycle affects which paths are visible

- **1-2: The Riddle Stones** (side-scroll)
  - Stone monuments with math/logic riddles block three bridges
  - Riddle 1: "I am greater than 5, less than 10, and odd. What numbers could I be?" (select all: 7, 9)
  - Riddle 2: Pattern completion (shapes/colors)
  - Riddle 3: Simple word puzzle
  - Fox companion hints after 30 seconds if stuck

- **1-3: The Hollow Tree** (top-down exploration)
  - Enter a massive hollow tree — explore rooms/tunnels inside
  - Puzzle: Redirect light beams using mirrors to illuminate dark passages
  - Collectible: 5 golden acorns hidden throughout
  - Mini-puzzle in each room: levers, pressure plates, color-matching

- **1-4: The Vine Labyrinth** (top-down exploration)
  - Navigate a living maze where walls slowly shift
  - Puzzle: Follow animal tracks to find safe path (wrong path = back to start of section)
  - Fox can sniff to reveal hidden paths (tap fox, then tap ground)
  - Timer element: Some passages only open briefly

- **1-5: The Unicorn's Glade** (side-scroll boss level)
  - Enchanted vines hold the unicorn — must solve a 3-part puzzle:
    - Part 1: Collect 4 elemental flowers (fire/water/earth/air) from around the glade
    - Part 2: Place them in correct altar positions (clues from earlier levels)
    - Part 3: Play a musical sequence on crystal chimes (simon-says style, 6 notes)
  - Unicorn joins as companion! Can fly over gaps in future levels

**STAGE 2: THE CRYSTAL CAVES** (4 levels)
*Companions: Fox + Unicorn*
*Goal: Restore light to underground crystal network*

- **2-1: The Entrance** (side-scroll)
  - Descend into caves, water dripping, bioluminescent fungi
  - Puzzle: Grow fungi by tapping in correct order to light the path
  - Platforming: Jump between crystal platforms over dark chasms
  - Collectible: 3 crystal shards

- **2-2: The Echo Chamber** (top-down)
  - Large cavern with sound-based puzzles
  - Puzzle: Tap stalactites to create melodies — match the echo pattern
  - Navigation: Map rooms by sound (shown as expanding rings)
  - Fox helps by pointing toward correct tunnels

- **2-3: The Underground River** (side-scroll)
  - Ride crystal rafts down underground river
  - Puzzle: Redirect water flow by placing/removing rocks
  - Obstacle: Whirlpools — navigate around using unicorn flight
  - Timing puzzle: Open/close sluice gates in sequence

- **2-4: The Crystal Heart** (top-down boss)
  - Massive crystal chamber — heart crystal is cracked
  - Puzzle: Rotate crystal lens pieces to redirect light beams to the heart
  - 3 phases of increasing complexity
  - On completion: Caves light up, reveal map to next stage
  - Dragon companion unlocked (small, friendly)

---

### PREMIUM STAGES ($4.99 unlock — "The Forgotten Realms Pack")

**STAGE 3: THE FLOATING ISLANDS** (4 levels)
- Sky archipelago connected by wind bridges
- New mechanic: Wind direction puzzles, gliding with unicorn
- Companion: Baby dragon can breathe small flames to melt ice blocks
- Boss: Reconnect 5 floating islands by solving gear/pulley puzzles

**STAGE 4: THE CLOCKWORK FORTRESS** (3 levels)
- Mechanical castle with gears, pistons, moving platforms
- New mechanic: Build simple machines (lever + fulcrum, ramp + ball)
- Puzzle focus: Rube Goldberg chains — place pieces to trigger chain reactions
- Boss: Fix the grand clock by placing gears correctly (math: gear ratios simplified)

**STAGE 5: THE PAINTED DESERT** (4 levels)
- Color-drained desert — restore color through puzzles
- New mechanic: Color mixing (red+blue=purple, etc.) to paint bridges/paths
- Puzzle: Match desert animal silhouettes to their habitats
- Boss: Paint a mural by solving a tangram-style puzzle

**STAGE 6: THE FROZEN PEAKS** (3 levels)
- Snowy mountains, ice physics (sliding)
- New mechanic: Temperature management — use dragon fire to melt ice, but not too much
- Puzzle: Ice block sliding puzzles (sokoban-style)
- Boss: Thaw the frozen guardian by solving heat-pipe routing puzzle

**STAGE 7: THE SUNKEN CITY** (4 levels)
- Underwater ruins with air bubble mechanics
- New mechanic: Buoyancy puzzles — heavy/light objects, water levels
- Puzzle: Decode ancient symbols using clues found throughout
- Boss: Raise the city by placing ancient power stones

**STAGE 8: THE SHADOW FOREST** (3 levels)
- Dark mirror of Stage 1 — familiar but twisted
- New mechanic: Shadow/light duality — some objects only visible in shadow
- Puzzle: Shadow puppet matching to unlock gates
- Boss: Unite shadow and light versions of the forest

**STAGE 9: THE DRAGON'S ARCHIVE** (3 levels)
- Ancient library maintained by dragons
- New mechanic: Book/scroll puzzles — arrange story pages in order
- Puzzle: Decode simple ciphers (A=1, B=2, etc.)
- Boss: Complete the ancient prophecy by filling in missing words (context clues)

**STAGE 10: THE STORM CITADEL** (4 levels)
- Lightning-powered floating fortress
- New mechanic: Electrical circuit puzzles (connect wires, switches)
- Puzzle: Navigate changing weather patterns
- Boss: Redirect lightning to power the citadel's shield

**STAGE 11: THE GARDEN OF TIME** (3 levels)
- Time-themed puzzles — see past/present of same location
- New mechanic: Toggle between two time periods to solve puzzles
- Puzzle: Plant seeds in past, harvest in present; build bridge in past, cross in present
- Boss: Synchronize two timelines to restore the garden

**STAGE 12: THE HOMECOMING FESTIVAL** (3 levels — finale)
- Return to Meadow Kingdom for grand celebration
- All companions reunited
- Final puzzles incorporate every mechanic learned
- Ending: Player crowned protector of the Forgotten Realms
- Credits with stats: puzzles solved, companions found, time played

---

## LEVEL ARCHITECTURE

### Side-Scroll Levels
- World width: 4000-8000px (vs 1600 in original)
- Parallax backgrounds (3 layers)
- Interactive objects highlighted with subtle shimmer
- Tap-to-move player + tap objects to interact
- HUD: top-left compass, top-right inventory (max 4 items)

### Top-Down Levels  
- Grid-based rooms, 20x15 tiles visible
- Room transitions via doors/tunnels
- Minimap in corner (fog-of-war style)
- Tap to move, tap objects to interact
- Light radius around player in dark areas

### Shared Systems
- Companion AI: follows player, has unique ability on tap
- Speech bubbles for dialogue (keep original style)
- Particle effects (keep original system)
- Sound: procedural chimes (keep original audio engine)
- Save progress: localStorage per-stage
- Hint system: companion offers hint after 45s stuck, full solution hint after 90s

---

## MONETIZATION

### Strategy: $4.99 one-time unlock
- Stages 1-2 (9 levels) = FREE
- Stages 3-12 (34 levels) = $4.99 "Forgotten Realms Pack"
- No ads, no consumables, no loot boxes — parent-friendly
- Unlock prompt appears naturally when starting Stage 3
- Payment via parent-gated modal (solve 3-digit multiplication to access payment)
- Stripe checkout or app store IAP when wrapped as mobile app

### Parent Gate
- "To unlock more adventures, ask a grown-up to help!"
- Math problem: e.g., "What is 24 x 17?" (too hard for target age to bypass)
- On correct answer: show payment options

---

## TECHNICAL ARCHITECTURE

### File Structure
Single HTML file (like original) BUT modular internal structure:
- Core engine (rendering, input, save/load, audio)
- Level data as JSON-like objects
- Each stage has its own init/update/draw/tap handler
- Shared puzzle components (riddle system, pattern matcher, circuit builder, etc.)

### Build Strategy (Hive Orchestration)
Given the size (~40-50k lines), build in layers:

**Layer 1: Core Engine** (1 Sonnet)
- Canvas setup, game loop, state machine
- Character creator (expanded)
- Player movement (side-scroll + top-down modes)
- Companion AI system
- Particle system, audio engine, speech bubbles
- Save/load, HUD, inventory
- Parent gate + unlock system
- Level loader architecture

**Layer 2: Puzzle Systems** (1 Sonnet)
- Pattern matching engine
- Riddle/quiz system (with difficulty)
- Light beam/mirror reflection
- Simon-says / musical sequence
- Sokoban (block pushing)
- Circuit/wire connection
- Color mixing
- Gear/machine building
- Cipher decoder
- Time-toggle (past/present)

**Layer 3: Stages 1-2** (1 Sonnet per stage, 2 total)
- Full level implementations for free content
- All art, puzzles, dialogue, transitions

**Layer 4: Stages 3-6** (1 Sonnet per 2 stages, 2 total)
- Premium content batch 1

**Layer 5: Stages 7-12** (1 Sonnet per 2 stages, 3 total)
- Premium content batch 2 + finale

**Layer 6: Integration + Polish** (1 Sonnet)
- Merge all pieces
- Bug audit
- Performance optimization
- Mobile touch optimization
