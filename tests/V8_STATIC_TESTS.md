# V8 Static Test Record

Commit: e90fba4c0aff92b1f5bb0045761518a4a420a31d

PASS
- V8 header present.
- Quantity guard rejects null, non-integer, negative, zero delivered, and totals exceeding delivered.
- newId() increments on an existing timestamp collision.
- Writes use forkspoon_delivery_v8; reads migrate from forkspoon_delivery_v7.
- Main/V7 branch remains untouched.

NOT_TESTED
- Browser UI interactions and localStorage migration in a real browser.
- Mobile/offline behavior and multi-tab concurrency.
