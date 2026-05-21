# [Task] Verify Firebase Android SHA-256 includes Play App Signing cert

## Summary
Confirm Firebase Android app registration includes the Play App Signing SHA-256 certificate used in distributed builds.

## Labels to apply
- type:task
- area:firebase
- area:android
- priority:p1
- status:ready

## Environment
- App version: N/A
- Build number: N/A
- Device: N/A
- Android version: N/A
- Play track: internal
- Firebase project id: TBD
- Package name: TBD

## Repro steps
1. Open Firebase console for target project.
2. Open Android app registration.
3. Compare registered SHA-256 fingerprints against Play App Signing certificate fingerprint.
4. Add missing fingerprint if absent.

## Expected result
Firebase app registration contains the active Play App Signing SHA-256 fingerprint.

## Actual result
TBD

## Logs or screenshots
Attach sanitized screenshots of certificate fingerprint match.

## Severity and impact
P1 - Missing SHA-256 can break auth/App Check behavior in signed builds.

## Acceptance criteria
- [ ] Play App Signing SHA-256 fingerprint verified
- [ ] Fingerprint added in Firebase if missing
- [ ] Verification evidence attached
