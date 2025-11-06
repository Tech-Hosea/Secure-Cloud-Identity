# Phase 8 — Device Lifecycle & Runbooks

## Objective
Define runbooks for lost/stolen devices and automate cleanup of inactive devices.

## Screenshots
1. **Lost Device Runbook**
<img width="1327" height="506" alt="lost device runbook" src="https://github.com/user-attachments/assets/57d3e659-b64e-46e1-9388-824f60734c1a" />

   *Caption:* “Verified wipe/retire workflow for lost corporate devices.”


## Notes
- Use Autopilot Reset for reprovisioning corporate laptops
- BYOD retire removes only corporate data

## Test Steps
- Simulate lost device → confirm Wipe/Retire triggers
- Confirm automated cleanup removes stale devices
