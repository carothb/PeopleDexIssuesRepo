# [Task] Refresh google-services.json and rebuild release

## Summary
Ensure release build uses the latest Firebase Android configuration by refreshing `google-services.json` and rebuilding.

## Labels to apply
- type:task
- area:firebase
- area:android
- priority:p1
- status:ready

## Environment
- App version: TBD
- Build number: TBD
- Device: N/A
- Android version: N/A
- Play track: internal
- Firebase project id: TBD
- Package name: TBD

## Repro steps
1. Download latest `google-services.json` for the target Firebase Android app.
2. Replace project config file in Android app module.
3. Build signed release artifact.
4. Validate config values in build output/runtime logs.

## Expected result
Release build contains current Firebase project identifiers and services initialize correctly.

## Actual result
TBD

## Logs or screenshots
Attach sanitized build output and runtime initialization evidence.

## Severity and impact
P1 - Stale config can cause runtime integration failures.

## Acceptance criteria
- [ ] Latest config file confirmed
- [ ] Release build succeeds
- [ ] Firebase initialization validated in test run
