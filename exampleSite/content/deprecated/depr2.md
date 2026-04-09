---
title:
date: 2025-03-01T10:00:00+00:00
removal_date: 2027-01-01
weight:
version:
---

#### `relocated` session event

`relocated` session event is deprecated in favour of `tab_relocated` and will be removed in a future version.

- Replace `relocated` with `tab_relocated` in your event listeners
- The new event carries an additional `ssid` field identifying the affected tab
