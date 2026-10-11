# BracketPop

Eight contenders. Seven choices. One champion.

BracketPop is a simple tournament game for debates that belong in a group chat. Pick a lineup, play through the matchups, and send your result or challenge friends to make their own picks.

## Play

Once GitHub Pages is enabled, visit **https://smarty-saini.github.io/bracketpop/**.

Create a bracket from scratch, or select one of the built-in themes. Each bracket is encoded in the URL, so a friend can play the exact same contenders without an account.

## How it works

The website is static HTML, CSS, and browser JavaScript. It has no server, no database, no third-party AI service, and no hosted analytics. The links contain the title and eight entries in URL parameters, so avoid including private information.

Results are individual, not a public vote tally. Anyone can make their own picks.

## Local run

Open `index.html` in a modern browser, or run `python3 -m http.server 8000` and visit http://localhost:8000.

## Publishing

In repository **Settings → Pages**, select **GitHub Actions** as the source. The included workflow publishes this repository on changes to `main`. It does not affect any other repository or website.

## Commercial plans

The game is currently free. Sponsorships and creator campaigns are possibilities for the future, but payments, subscriptions, commercial dashboards, and hosted accounts have **not** been implemented.

## Notes

Please use respectful, original topics. Do not put sensitive personal information in shareable URLs. See the Privacy and Terms pages for current limitations.

Copyright © 2026 SmaRTy Saini Corp. All rights reserved. No open-source license is granted.