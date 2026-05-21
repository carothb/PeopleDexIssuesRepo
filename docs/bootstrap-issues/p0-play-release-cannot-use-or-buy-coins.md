# [P0] Play release cannot use or buy coins

## Summary
Users on Play release cannot spend PD Coins and cannot complete new coin purchases.

## Labels to apply
- type:release
- area:billing
- area:coins
- priority:p0
- status:ready

## Environment
- App version: TBD
- Build number: TBD
- Device: Multiple
- Android version: Multiple
- Play track: production
- Firebase project id: TBD
- Package name: TBD

## Repro steps
1. Install latest production build from Play.
2. Sign in with a test account that can purchase and spend coins.
3. Attempt to buy a coin pack.
4. Attempt a coin spend action.

## Expected result
Purchase and coin-spend flows complete successfully.

## Actual result
Purchase and/or spend flows fail.

## Logs or screenshots
Attach sanitized billing response codes, backend error IDs, and UI evidence.

## Severity and impact
P0 - Direct monetization impact and release risk.

## Acceptance criteria
- [ ] Purchases succeed for approved tester accounts
- [ ] Coin balance updates after purchase
- [ ] Coin spend succeeds and decrements correctly
- [ ] No blocking billing/App Check errors in production logs
