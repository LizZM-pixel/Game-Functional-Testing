Tester: Elizabeth Aquino
Game URL: https://chromedio.com/
Date: 2025-10-01
| ID | Priority | Title | Preconditions | Steps | Expected Result |
|--------|----------|-------------------|------------------|------------------------|--------------------------|
| TC-001 | P0 | Game loads | Browser is open | 1. Navigate to game URL | Start screen is visible |
| TC-002 | P0 | Start run | Game is loaded | 1. Press Spacebar | Dino starts running |
| TC-003 | P0 | Jump works | During gameplay | 1. Press Spacebar | Dino jumps correctly |
| TC-004 | P0 | Collision ends run | During gameplay | 1. Run into an obstacle | Game Over screen is shown |
| TC-005 | P0 | score increases | Dino is running | 1.Wait for 10 seconds | Score value increases |
| TC-006 | P0 | Restart resets score |After Game Over | 1. Press Restart | Score resets to 0 |
| TC-007 | P01 | Responsive input | During gameplay | 1. Press Spacebar repeatedly | Jumps trigger immediately without delay |
| TC-008 | P02 | Window resize handling | Game is loaded | 1. Resize browser window | Game scales without UI breaking |
| TC-009 | P02 | Focus loss handling | During gameplay | 1.Switch to another browser tab,return | Game pauses/resumes safety(per design) |
