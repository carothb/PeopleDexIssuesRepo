# [Task] Verify in-app products active and tester purchase claim flow

## Summary
Confirm Play Console in-app products are active and tester purchase/entitlement claim flow works end-to-end.

## Labels to apply
- type:task
- area:billing
- area:coins
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
1. Verify target in-app products are active in Play Console.
2. Install internal track build with tester account.
3. Purchase each configured coin product.
4. Confirm receipt processing and entitlement claim.
5. Confirm refund/cancel handling (if testable).

## Expected result
All active products are purchasable and coin entitlement claim succeeds reliably.

## Actual result
TBD

## Logs or screenshots
Attach sanitized billing logs and entitlement confirmation evidence.

## Severity and impact
P1 - Product activation/purchase failures break monetization testing.

## Acceptance criteria
- [ ] All intended products marked active
- [ ] Tester purchase succeeds per product
- [ ] Coin entitlement claims update balance correctly
- [ ] Error handling validated for failed/canceled purchases
