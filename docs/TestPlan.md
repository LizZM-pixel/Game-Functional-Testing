#Test Plan — 2D Runner (Dino Game)

**Tester:** Elizabeth Aquino
**Game Under Test (GUT):** Dino Runner (Chrome Dinosaur Game)
**URL:** https://chromedino.com/
**Date:** 2025-10-01

---

## 1. Objectives
- Validate the core game loop: start, jump, avoid obstacles, collision, score, restart.
- Verify that basic UI elements are visible and readable.
- Check input responsiveness and collision accuracy.

---

## 2. Scope
**In-Scope:**
- Keyboard input (Spacebar to jump).
- Obstacle generation and collision detection.
- Score increment and reset on restart.
- “Game Over” and restart functionality.

**Out-of-Scope:**
- Global leaderboards.
- Memory optimization.
- Multiplayer functionality.

---

## 3. Environments
- Browser: Chrome (latest version).
- Operating System: Windows 10/11, MacOS.
- Optional: Mobile browser (Safari on iOS, Chrome on Android).

---

## 4. Test Types
- **Smoke testing** (basic quick test).
- **Functional testing** (detailed functionality tests).
- **Exploratory testing** (free exploration for unexpected behaviors).
- **Basic performance heuristics** (play for several minutes and observe stability).

---

## 5. Entry / Exit Criteria
- **Entry:** Game loads and is accessible in the browser.
- **Exit:** All main test cases executed, no critical blockers remain.

---

## 6. Risks & Mitigations
- **Input delay:** measure if the jump responds late.
- **Collision inaccuracy:** test collisions near obstacle edges.
- **Score not resetting:** confirm score resets to 0 after restart.

---

## 7. Deliverables
- Executed checklists (smoke, regression).
- Test cases with pass/fail status.
- Bug reports with evidence.
- Final test report.

---

## 8. Roles & Communication
- Individual portfolio project.
- All evidence and artifacts will be stored in this repository.
