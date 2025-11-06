# Phase 8 — Device Lifecycle & Runbooks

## Objective
Define runbooks for lost/stolen devices and automate cleanup of inactive devices.

## Screenshots
1. **Lost Device Runbook**
   ![lost_device_runbook.png](lost_device_runbook.png)
   *Caption:* “Verified wipe/retire workflow for lost corporate devices.”

2. **Automation Flow**
   ![automation_flow.png](automation_flow.png)
   *Caption:* “Scheduled device cleanup automation for devices inactive >90 days.”

## Notes
- Use Autopilot Reset for reprovisioning corporate laptops
- BYOD retire removes only corporate data

## Test Steps
- Simulate lost device → confirm Wipe/Retire triggers
- Confirm automated cleanup removes stale devices
