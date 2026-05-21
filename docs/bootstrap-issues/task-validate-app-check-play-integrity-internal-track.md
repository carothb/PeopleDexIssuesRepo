# [Task] Validate App Check Play Integrity attestation in internal track

## Summary
Validate Firebase App Check using Play Integrity attestation in internal testing track.

## Labels to apply
- type:task
- area:firebase
- area:android
- priority:p1
- status:ready

## Environment
- App version: TBD
- Build number: TBD
- Device: Physical Android device
- Android version: TBD
- Play track: internal
- Firebase project id: TBD
- Package name: TBD

## Repro steps
1. Install build from internal track.
2. Launch app and trigger backend request protected by App Check.
3. Confirm App Check token issuance and validation.
4. Verify no fallback or debug token path is used.

## Expected result
Play Integrity attestation succeeds and protected requests are accepted.

## Actual result
TBD

## Logs or screenshots
Attach sanitized client/server logs confirming App Check validation.

## Severity and impact
P1 - App Check failures can block backend access in production-like distribution.

## Acceptance criteria
- [ ] App Check token issued in internal track build
- [ ] Protected endpoint calls succeed with valid attestation
- [ ] No unexpected App Check rejections observed
