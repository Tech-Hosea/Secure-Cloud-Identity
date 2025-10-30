# Phase 5 — Security Baselines & Hardening

## Objective
Deploy Windows 11 baselines, BitLocker, Defender ASR rules, and update rings.

## Screenshots
1. **Windows 11 Baseline**
<img width="362" height="387" alt="Windows10 11Security Baseline" src="https://github.com/user-attachments/assets/a1ea12d3-28b1-4a79-b7b1-5a8575d76457" />

   *Caption:* “Applied Windows 11 security baseline to pilot devices.”

2. **ASR Rules**
<img width="443" height="242" alt="Attack Surface Reduction" src="https://github.com/user-attachments/assets/d036c749-a36e-447c-85f5-373bb0769f52" />

   *Caption:* “Attack Surface Reduction rules enabled to block credential theft and macros.”

3. **Update Ring**
<img width="437" height="443" alt="Update rings" src="https://github.com/user-attachments/assets/39f67ba0-9bcf-4cbf-b8cc-c364a0cff8ef" />

   *Caption:* “Pilot update ring configured for 7-day feature deferral.”

## Notes
- BitLocker encryption enforced with TPM
- Policies first deployed to pilot group before full rollout

## Test Steps
- Confirm policy compliance in Endpoint Manager → Devices → Monitor
