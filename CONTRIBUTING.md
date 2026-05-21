# Contributing to PeopleDex public issue tracking

Thanks for helping us improve PeopleDex.

## How to report bugs

1. Open **Issues** and choose the most relevant template:
   - **Bug report** for defects and regressions
   - **Release blocker** for issues that block Android rollout
   - **Task checklist** for scoped implementation/verification work
2. Complete every required field, especially environment details and repro steps.
3. Add the most specific area label(s): `area:android`, `area:firebase`, `area:billing`, `area:coins`.

## What not to include

This repository is public. Do **not** include:

- API keys, auth tokens, or secrets
- Personal data (email addresses, phone numbers, payment info, device IDs)
- Private/internal links, logs, or repository details

If sensitive details are required for diagnosis, maintainers will provide a private follow-up path.

## Triage labels used by maintainers

- **Type**: `type:bug`, `type:release`, `type:task`
- **Area**: `area:android`, `area:firebase`, `area:billing`, `area:coins`
- **Priority**: `priority:p0`, `priority:p1`
- **Status**: `status:needs-repro`, `status:blocked`, `status:ready`

Triage flow:

1. Validate template completeness
2. Add/update `status:*`
3. Assign `priority:*` based on impact
4. Confirm resolution with acceptance criteria

## SLA expectations

- **P0**: Initial maintainer response target within **4 business hours**
- **P1**: Initial maintainer response target within **1 business day**

These are targets, not guarantees. Complex incidents may require more time.

## Submitting screenshots and logs safely

- Redact usernames, IDs, email addresses, tokens, and order/payment references.
- Share only the minimal log window needed to diagnose the issue.
- Prefer screenshots over raw log dumps when possible.
- If a full log is needed, wait for private disclosure instructions from maintainers.
