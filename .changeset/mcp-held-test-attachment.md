---
'e2e': patch
'@e2e-dev/core': patch
---

Attach to a test held at `screen.pause()` or `e2e run --step` with
`open_session {attach: "p1"}` in `e2e mcp`. Use the ID printed in the
prompt. Closing the session detaches and leaves the test held.
