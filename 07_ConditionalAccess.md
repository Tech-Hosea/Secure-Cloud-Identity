# Phase 6 — Conditional Access

## Objective
Block non-US sign-ins, use report-only mode, and test with What-If simulator.

## Screenshots
1. **Named Location**
<img width="692" height="443" alt="Named Location" src="https://github.com/user-attachments/assets/a00694b0-b229-42f3-a668-02d8043758f4" />

   *Caption:* “Created LOC_US for trusted US location.”

2. **Conditional Access Policy**
<img width="416" height="420" alt="Policy Overview" src="https://github.com/user-attachments/assets/a728c40e-b2c2-4482-b705-bd963a6848c4" />

   *Caption:* “Report-only CA policy to block non-US sign-ins for pilot users.”


## Notes
- Exclude break-glass admin from policy
- Test pilot users before enforcement

## Test Steps
- VPN sign-in attempt outside US → verify policy triggers
