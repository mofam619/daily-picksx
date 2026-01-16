**# Today's Bet Options

Simple static site that shows "safe", "medium", and "higher odds" picks for today's soccer matches using TheSportsDB eventsday API.

Notes
- Odds shown are simulated / illustrative only.
- The app is a static HTML file and can be hosted with GitHub Pages.

How to publish
1. Create a new repo on GitHub (e.g. `todays-bet-options`) and push this code to the `main` branch.
2. In the repo Settings → Pages, set the source to the `main` branch (root) and save.
3. Wait a minute — your site will be available at `https://<your-username>.github.io/<repo-name>/`.

Or publish with gh-pages branch:
- Create branch `gh-pages` and push `index.html` as the root of that branch. GitHub Pages will serve it automatically.

Local testing
- Open `index.html` in a browser (some browsers may block the remote API request when opening from file://; use a local server like `npx serve` or `python -m http.server`).

License
- Add a license file if you want to allow reuse.**
