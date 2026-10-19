# Engineering Case Studies

Bounded technical accounts based on recorded internal project milestones. No private implementation details or source code are disclosed.

## 1 — Planning-aware calendar integration

**Problem:** Calendar displays must connect to existing planning data without silently creating a parallel and divergent task database.

**Delivered scope (October 2026):** month, week and day views; a 30-day agenda; existing tasks, milestones, decisions and checkpoints shown; editing of existing tasks and project linkage.

**Boundary:** dedicated persistent calendar events, recurring meetings and recurrence semantics were not delivered in this milestone.

**Verification:** the internal milestone report records successful TypeScript/build checks, 17 targeted tests and real-app testing. These are *reported private checks*, not publicly reproducible tests.

**Trade-off:** ship useful views of existing records before adding the more complex independent event domain.

## 2 — Prototype versus integrated academic workbench

**Problem:** A standalone demo may work visually while failing to participate in the actual desktop app.

**Delivered scope:** an academic workbench routed through the real application, with a navigable file tree, file selection and contextual open/split interactions.

**Validation principle:** verify in the actual app path; prototype parity alone is insufficient.

**Boundary:** no claim of a complete document editor, generalized workspace synchronization or universal file system.

## 3 — Ambient UI as a bounded module

**Problem:** Multiple visual states across seasons and times of day can complicate an interface if embedded across unrelated business logic.

**Delivered scope:** 16 seasonal/time-of-day visual assets, compressed asset delivery, automatic transitions and manual preview controls.

**Principle:** isolate aesthetic transitions from core workflow behavior and verify them in the integrated desktop application.

## Project ownership & AI-assisted engineering

ENNEAD is independently directed and uses AI-assisted tools for some research and implementation. Public materials distinguish system specifications, acceptance criteria, integration and review responsibilities from claims of individually authored code. Implemented does not automatically mean publicly shipped or independently verified.

**Further evidence planned:** sanitized actual-app screenshots, short guided walkthrough and selectively reproducible generic demonstrations, all subject to disclosure review.
