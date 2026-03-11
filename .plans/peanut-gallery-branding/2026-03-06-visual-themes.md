# Peanut Gallery Branding - The Cast Direction

**Date:** 2026-03-06  
**Status:** In Progress  
**Agent:** Chip 🐱‍💻

---

## Goal

Define and test "The Cast" - AI-generated realistic human personas who serve as the Peanut Gallery focus group. This is the PRIMARY visual direction. Starting with **one cast member (Alex "The Scroller" Chen)** for exploration, then expanding.

---

## Overview

**The Cast Concept:** AI-generated realistic human personas with distinct personalities, environments, and reaction styles. Each cast member represents a specific audience segment and content consumption pattern.

**Starting Point:** Alex "The Scroller" Chen (existing persona from emotion-engine):
- **Age:** 17, Gen Z digital native
- **Core Truth:** Abandons content if hook takes longer than 3 seconds
- **Habits:** 200+ short-form videos/day, TikTok-trained
- **Environment:** Urban bedroom, phone-centric, colorful LED lighting, posters, casual chaos
- **Vibe:** Impatient, authentic, brutally honest, algorithm-literate

**Tag/Category System:** Users will select cast members based on:
- **Power Users (Devs):** YAML config in repo with direct file links
- **Marketers/Non-Devs:** GUI with recommendations based on content analysis + tags

**Video Workflow:** **Option B - Persona in Their Environment**
- Show cast member in their natural space (bedroom, office, cafe, etc.)
- Environment tells the story of who they are
- Cutaway shots of reactions vs. play-by-play corner video
- More useful for conveying persona identity to users

**Realism Level:** Photorealistic (can adjust if uncanny valley becomes an issue)

---

## Tasks

### Task 1: Document Alex's Visual Profile

**SubAgent:** `primary`  
**Prompt:** Based on the existing impatient-teenager persona (/workspace/projects/opentruth/emotion-engine/personas/impatient-teenager.md), create a visual profile document that translates behavioral traits into visual direction. Include:
- Physical appearance description (age, style, hair, clothing aesthetic)
- Environment description (bedroom setup, lighting, decor, phone/laptop placement)
- Typical poses/expressions (scrolling, skeptical look, genuinely interested, bored)
- Color palette for their environment (LED colors, wall colors, accent tones)
- Props that tell their story (phone, headphones, posters, snacks, etc.)
- Camera angles that work best (close-up on phone + face, wider room shot, over-shoulder)

This doc will be used for image generation prompts. Save to: `/home/derrick/.openclaw/workspace/projects/peanut-gallery/cast/impatient-teenager/visual-profile.md`

**Folders Created:**
- `cast/impatient-teenager/` (already exists)

**Files Created:**
- `cast/impatient-teenager/visual-profile.md`

**Status:** ⏳ Pending

**Results:** 

---

### Task 2: Generate Alex Character Sheet

**SubAgent:** `vision` (using nano-banana-pro skill)  
**Prompt:** Generate photorealistic character sheet images for Alex "The Scroller" Chen (17, Gen Z, urban, they/them). Create:
- Portrait (front view, neutral expression, good lighting)
- Profile view (side view, for consistency reference)
- Environment shot 1 (in bedroom, scrolling on phone, LED lighting, casual)
- Environment shot 2 (reacting to content, skeptical expression)
- Environment shot 3 (genuinely interested/engaged with content)
- Close-up (face + phone, showing scroll-ready thumb position)

Style: Photorealistic, natural lighting with LED accents, urban teen bedroom environment, authentic not staged.

Save images to: `/home/derrick/.openclaw/workspace/projects/peanut-gallery/cast/impatient-teenager/assets/portraits/`

**Folders Created:**
- `cast/impatient-teenager/assets/portraits/` (already exists)

**Files Created:**
- `cast/impatient-teenager/assets/portraits/character-*.png`

**Status:** ⏳ Pending

**Results:** 

---

### Task 3: Test Emotion/Reaction Consistency

**SubAgent:** `vision` (using nano-banana-pro skill)  
**Prompt:** Test generating Alex with consistent facial features across different emotional states. Generate 6-8 images of the same character (Alex) showing:
- Bored/skeptical (about to scroll)
- Intrigued (raised eyebrow, leaning in)
- Genuinely interested (engaged, watching intently)
- Excited/hooked (eyes wide, slight smile)
- Disappointed/cringe reaction
- Surprised (pattern interrupt moment)

Keep environment consistent (bedroom with LED lighting). Goal: Verify we can maintain character consistency while changing expressions.

Save images to: `/home/derrick/.openclaw/workspace/projects/peanut-gallery/cast/impatient-teenager/assets/reactions/`

**Folders Created:**
- `cast/impatient-teenager/assets/reactions/` (already exists)

**Files Created:**
- `cast/impatient-teenager/assets/reactions/reaction-*.png`

**Status:** ⏳ Pending

**Results:** 

---

### Task 4: Research Video Generation Feasibility

**SubAgent:** `research`  
**Prompt:** Research AI video generation tools for creating short reaction clips (10-30 seconds) of a consistent character in their environment. Investigate:
- **Tools:** Runway Gen-2/Gen-3, Pika Labs, D-ID, HeyGen, SadTalker, AnimateAnyone, Kaiber
- **Capabilities:** Character consistency, environment consistency, emotion transitions
- **Workflows:** Image-to-video, text-to-video, audio-driven animation
- **Limitations:** Length, quality, consistency, cost, learning curve
- **Best For:** Cutaway reaction shots (not play-by-play corner video)

Create a feasibility report with:
- Top 2-3 recommended tools for Peanut Gallery use case
- Sample workflow (generate Alex images → animate to video)
- Current limitations to be aware of
- Fallback option (static images + emotion-engine text output)
- Estimated cost/time per video

Save to: `/home/derrick/.openclaw/workspace/projects/peanut-gallery/cast/impatient-teenager/video-feasibility.md`

**Files Created:**
- `cast/impatient-teenager/video-feasibility.md`

**Status:** ⏳ Pending

**Results:** 

---

### Task 5: Create Cast Member Tag/Category System

**SubAgent:** `primary`  
**Prompt:** Design a tag/category system for cast members that will be used for:
- **GUI Recommendations:** System examines uploaded content and recommends cast members
- **YAML Config (Devs):** Direct cast member selection with custom parameters
- **Future Expansion:** Easy to add new cast members with new tags

Create a taxonomy document with:
- Core tag categories (age group, tech-savviness, content preferences, patience level, platform preferences, etc.)
- Example tags for Alex Chen
- How tags map to content types (e.g., "short-form expert" for TikTok-style content)
- YAML config example for developers
- GUI mockup description (how recommendations are shown to non-devs)

Save to: `/home/derrick/.openclaw/workspace/projects/peanut-gallery/cast/tag-system.md`

**Files Created:**
- `cast/tag-system.md`

**Status:** ⏳ Pending

**Results:** 

---

### Task 6: Create The Cast Visual Direction Doc

**SubAgent:** `primary`  
**Prompt:** Create the primary visual direction document for "The Cast" that will replace/supplement the existing visual-directions.md. Include:
- Concept overview (The Cast as primary direction)
- Alex Chen case study (full example from persona to visual)
- Image generation guidelines (prompts, consistency techniques, best practices)
- Environment design principles (how spaces tell persona stories)
- Video workflow options (cutaway reactions vs. play-by-play)
- Tag/category system overview
- Integration with emotion-engine project
- Expansion plan (how to add new cast members)
- Pros/cons vs. previous directions (Theater, Panel, Mascot)

Save to: `/home/derrick/.openclaw/workspace/projects/peanut-gallery/cast/visual-direction-cast.md`

**Files Created:**
- `cast/visual-direction-cast.md`

**Status:** ⏳ Pending

**Results:** 

---

## Final Results

**Status:** ⏳ Not Started

**What We Built:** 

**Commits:**

**Lessons Learned:** 

---

*Plan updated 2026-03-06 - Focused on Alex Chen as first cast member, Option B (environment-based) video workflow*
