# Life Knowledge Base

A systematic approach to life planning, professional growth, and knowledge management. This repository serves as a "Second Brain" and strategic engine for aligning daily actions with long-term vision.

## Philosophy
- **Connection First:** Prioritizing depth in relationships and work.
- **Equilibrium:** Balancing logic and emotion.
- **Resistance is Growth:** Lean into the difficult tasks.

## Directory Structure

### Pillars
- **`Personal/`**: Health, finance, relationships, and personal goals.
- **`Work/`**: Professional development, technical leadership, and career growth.

### Pillar Components
- **`Inbox/`**: Granular file-per-task capture for processing.
- **`Knowledge/`**: A curated library of reference materials, ideas, and documentation. Managed via a `MANIFEST.md`.
- **`Projects/`**: Active efforts within each pillar.
- **`Journal/`** (Personal): Daily reflections and annual goal tracking.

### System
- **`Reference/`**: Core values, principles, and habit frameworks.
- **`Templates/`**: Standardized formats for journals, decisions, and research.
- **`plan.md`**: The 10-year vision and life chapter framework.

## Workflows

### 1. Morning Alignment (Franklin Method)
Each morning begins with the prompt: *"What good shall I do this day?"*
- Review the **10-Year Vision** (`plan.md`).
- Review **Annual Goals** (`Personal/Journal/2026/goals.md`).
- Define 3-5 high-impact outcomes that ladder up to these goals.

### 2. Knowledge Management
- New reference items are added to `Knowledge/`.
- Every entry must be cataloged in the pillar's `MANIFEST.md` to ensure discoverability and prevent information rot.

### 3. Agent Protocol
Agents (like Claude) should:
- Respect the boundaries between `Work/` and `Personal/`.
- Use pillar-specific tagging (`#context/personal` or `#context/work`).
- Refer to `AGENTS.md` in the respective pillar for specific instructions.

## Tags
- `#context/personal`
- `#context/work`
- `#personal/health`, `#personal/finance`, `#personal/goals`
- `#work/leadership`, `#work/technical`, `#work/sideproject`
