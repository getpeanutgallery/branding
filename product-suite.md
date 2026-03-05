# Peanut Gallery - Product Suite

## Overview

The Peanut Gallery product suite provides automated persona-based feedback for content creators. Each component is named to maintain brand cohesion while clearly communicating its function.

---

## Components

### 1. Peanut Gallery Studio
**Type:** Web Application  
**Purpose:** Primary user interface for uploading videos, selecting personas, and receiving feedback.

**Features:**
- Video upload & processing
- Persona selection interface
- Feedback dashboard
- Session history & export

**Naming Rationale:** "Studio" evokes a creative workspace where content is crafted and refined. It positions the tool as a professional environment for iteration, not just a passive feedback collector.

---

### 2. Peanut Gallery CI
**Type:** GitHub Action  
**Purpose:** Automated testing in CI/CD pipelines to validate content against personas before merge/deploy.

**Features:**
- Pre-commit video validation
- PR comment integration
- Failure thresholds & gating
- Badge/status integration

**Naming Rationale:** "CI" is the standard industry term for Continuous Integration. Keeping it simple and recognizable ensures developers immediately understand its purpose. The "Peanut Gallery" prefix maintains brand connection.

---

### 3. Peanut Gallery Cast
**Type:** Persona Library  
**Purpose:** Community-contributed SOUL.md persona files that define feedback styles and perspectives.

**Features:**
- SOUL.md persona definitions
- Community marketplace
- Rating & discovery
- Custom persona creation

**Naming Rationale:** "Cast" continues the theater/audience metaphor inherent in "Peanut Gallery." Personas are the "cast of characters" providing feedback. It's warmer than "Library" and suggests personality, not just data.

---

### 4. Peanut Gallery Connect
**Type:** REST/GraphQL API  
**Purpose:** Third-party integrations with tools like Figma, YouTube, Vimeo, Descript, etc.

**Features:**
- Video ingestion endpoints
- Feedback retrieval
- Webhook notifications
- OAuth integrations

**Naming Rationale:** "Connect" emphasizes the integration/bridge function. It's more active and friendly than "API" while remaining professional. Signals that this is how external tools "connect to" the Peanut Gallery ecosystem.

---

### 5. Peanut Gallery CLI
**Type:** Command-Line Interface  
**Purpose:** Local development tooling for batch processing, scripting, and headless workflows.

**Features:**
- Batch video processing
- CI/CD scripting (alternative to GitHub Action)
- Persona management
- Configuration & auth

**Naming Rationale:** "CLI" is the universal standard for command-line tools. No need to be clever here—clarity wins. Developers expect this naming convention.

---

## Naming System Summary

| Component | Name | Pattern |
|-----------|------|---------|
| Web App | Peanut Gallery **Studio** | Creative workspace metaphor |
| GitHub Action | Peanut Gallery **CI** | Industry-standard abbreviation |
| Persona Library | Peanut Gallery **Cast** | Theater/audience metaphor |
| API | Peanut Gallery **Connect** | Integration/bridge metaphor |
| CLI | Peanut Gallery **CLI** | Industry-standard abbreviation |

**Brand Hierarchy:** All products inherit the "Peanut Gallery" master brand as the primary identifier, followed by a functional descriptor. This ensures:
- Immediate brand recognition
- Clear functional understanding
- Room for future product expansion
- Consistent naming across documentation, marketing, and code

---

## Visual Identity Notes

When displaying product names:
- Use **Peanut Gallery** as the lockup (logo + wordmark)
- Product descriptors (Studio, CI, Cast, Connect, CLI) can be styled as subtitles or secondary text
- Maintain consistent typography hierarchy across all products

---

*Document created: 2026-03-05*  
*Location: `~/.openclaw/workspace/projects/opentruth/branding/product-suite.md`*
