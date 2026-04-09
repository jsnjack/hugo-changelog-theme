---
title:
date: 2024-01-10T10:00:00+00:00
removal_date: 2026-06-01
weight:
version:
---

#### `tabIndex` parameter in session events

`tabIndex` parameter is deprecated for session events `tab_control`, `tab_paused`, `tab_resumed`. Use `ssid` parameter instead.

- Update all `tab_control` listeners to read `ssid` instead of `tabIndex`
- Update all `tab_paused` listeners to read `ssid` instead of `tabIndex`
- Update all `tab_resumed` listeners to read `ssid` instead of `tabIndex`
