# BadmintonAI Live

The public web page behind BadmintonAI tournament links. Anyone with a link can follow a
tournament's matches, results and standings in a browser, without the app.

- Links are temporary and created in the app by an organiser; an expired or cancelled link stops working.
- PIN-protected tournaments ask for their 4-digit PIN. Invitation-only tournaments are never shown.
- What a visitor can see is decided by the server, not by this page. The page holds only the
  server address and its public (publishable) key, the same ones built into the app.

This repository contains only the built page. The source is `web/viewer` in the private
BadmintonAI repository (built from 2bbd0cb); rebuild there and copy `dist/` here to update.
