# AUT Secure Exam – test server link

`link.json` holds the current address of the AUT Secure Exam **public test server** (a free Cloudflare tunnel from the
organiser's PC; the address changes every time it starts). `tools/public-test.ps1` in the main project updates it.

- The Android TEST app and the Windows app read `link.json` and connect by themselves.
- People open **https://ramzanali-blip.github.io/aut-exam-link/** and are forwarded to the current server
  (add `#/english/` or `#/` for English practice or the portal).

Only the link is stored here: no code, no data, no passwords.
