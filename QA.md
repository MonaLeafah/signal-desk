# Verification record

Tested October 9, 2026 with Node 24 and Ramona Chrome.

Five core tests pass: exact public watchlist normalization, release/push/license comparison, restoration/source restrictions, export labels, and rejection of missing counts. Syntax checks pass. A pinned, read-only GitHub Actions workflow runs on Linux, Windows, and macOS; consult Actions for the remote result.

The actual browser fetched all three public sources and replaced the fictional fixture. Review was blocked for fictional/imported data and blank notes. A human note permitted review; editing it reset the review. The downloaded three-file ZIP passed independent CRC validation and contained the Markdown briefing, JSON snapshot, source mode, sources, dates, and draft states.

A saved JSON snapshot reopened as unverified, with reviews reset. A live refresh compared it with current sources; unchanged release/push/license fields were reported accurately despite a changed star count. Undo restored the prior snapshot and note. Malformed JSON showed an error without replacing the current records. Loading disabled editing and competing mutations. Browser error/warning logs were empty during these checks.

Desktop and 390-pixel mobile layouts were visually inspected. The mobile document width matched its available 375-pixel viewport. Labels, visible focus, reduced motion, and keyboard-operable standard controls are included. This is practical verification, not formal accessibility certification or a full cross-browser audit.

API failure handling is implemented to retain the prior snapshot, with a 20-second timeout; a real remote outage was not induced during this browser session. The demo has no measured customer outcome, automatic interpretation, monitoring, or publication. Saving before reload is required. Every live refresh starts fresh draft human notes; undo recovers the previous snapshot.
