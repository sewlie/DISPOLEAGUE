# FOUNDING XI website prototype

A static HTML/CSS/JavaScript landing page for a proposed NYC 7v7 indoor football league.

## Files
- `index.html` — page content and structure
- `style.css` — layout, typography, colors, responsive behavior
- `script.js` — mobile navigation, fictional sample teams, interest-form behavior

## Run locally
1. Download and unzip the project folder.
2. Open the `founding-xi-website` folder in Visual Studio Code.
3. Open `index.html` in a browser, or use the VS Code Live Server extension.
4. The fonts load from Google Fonts when you have an internet connection. The page still works with fallback fonts offline.

## Configure the interest form
The current form is a prototype and does not store or send submissions. To enable the mail-draft behavior:
1. Open `script.js`.
2. Find `const CONTACT_EMAIL = "replace-with-your-league-email@example.com";`
3. Replace the placeholder with an inbox you control.
4. Save and test. Submitting opens the visitor's email app; it does not send the email automatically.

For a public launch, use a reputable form backend or form service, add an appropriate privacy notice, protect submissions against spam, and test data handling. Do not collect more personal data than necessary.

## Before publishing
- `FOUNDING XI` is a working name only. Check name and trademark availability before adopting it.
- The teams in the demo are fictional samples, not real participants.
- Season dates, venue, fees, competition rules, and team participation are not confirmed.
- Have New York counsel review the proposed dispensary team model and all cannabis-related sponsorship, advertising, apparel, event, and venue placements before publishing sponsor assets.
- Replace any demo content with verified information only.
