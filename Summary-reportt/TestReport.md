# Test Report — Dino Runner


Tester: Elizabeth Aquino

Date: 2025-10-02

Environment: Chrome 128 / Windows 11

## Scope


- Functional testing of Chrome Dino Runner focusing on core gameplay loop, input responsiveness, scoring, and restart functionality.
  

## 2. Test Execution Summary

| Category | Total | Passed | Failed | Blocked |
|----------------|-------|--------|--------|---------|
| Smoke Tests | 7 | 7 | 0 | 0 |
| Test Cases | 9 | 7 | 2 | 0 |

## 3. Bug Summary

| Bug ID | Title | Severity | Priority | Status |
|----------|------------------------------|----------|----------|----------|
| BUG-001 | Score not reset after restart | Major | P1 | Open |
| BUG-002 | Jump delay causes late response | Major | P1 | Open |

##Conclusion

The Dino Runner game is partially functional.

Core smoke tests passed successfully (game loads, jump, collisions, restart visible).

2 critical/major issues were identified which may impact gameplay experience.


**Recommendation:**  Fix BUG-001 and BUG-002 before release.
