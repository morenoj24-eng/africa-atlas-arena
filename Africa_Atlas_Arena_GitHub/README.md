# Africa Atlas Arena

A classroom geography game for 1–4 students sharing one device. Find countries and locations on the supplied numbered Africa map.

## Publish on GitHub Pages

1. Extract the ZIP on your computer.
2. Create a GitHub repository, for example **africa-atlas-arena**. A public repository is the simplest option for free GitHub Pages.
3. Upload the extracted files to the repository's top level, then commit them to **main**. Do not upload only the ZIP or put the game inside an extra folder.
4. Check that **index.html**, **game.js**, and **classroom-map.jpg** appear together at the top level.
5. Open **Settings → Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select **main** and **/(root)**, then **Save**.
8. Wait for GitHub to finish publishing. Return to Pages and open **Visit site**.
9. Share that website link with students—not the repository's file-view link.

The address normally looks like https://YOUR-USERNAME.github.io/africa-atlas-arena/ . Use the actual link GitHub shows.

No installation, build command, API keys, paid mapping service, or ChatGPT sign-in is required. The included .nojekyll file disables Jekyll processing; it may be hidden by your file browser.

Official instructions:
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Classroom play

- Choose 1–4 players and enter names.
- Choose all Africa or North, South, East, West, or Central.
- Choose 3, 6, 9, or **All worksheet locations**. Short matches are capped at the number of locations in the selected region.
- Complete Map gives each player every selected location once.
- The map includes exactly **1–52**. Western Sahara (#38) is a disputed territory included as a worksheet location. Options 53–55 are excluded.
- Choose 30 seconds, 60 seconds, or no timer.
- Click a printed map number or use the number menu; lock one guess per turn.
- Use zoom for small labels. Click the printed label, not arbitrary points inside a country.
- Country points: 100, 200, or 300. Correct timed answers earn up to 20 speed points.
- Regional hint: half country points and no speed bonus.
- Each player's one boost doubles country points for a correct guess, or deducts those country points for a miss; totals cannot go below zero.
- Finish with standings and a missed-location review.

Players take turns on one shared screen. Separate computers run independent matches; there are no online rooms or synchronized multiplayer sessions. Names and scores remain in page memory, and refreshing clears the match. In full-map games, each player receives an independently shuffled set with matching difficulty tiers per round.

## Files

- index.html — layout, styles, and map container
- game.js — location list, settings, turns, scoring, and results
- classroom-map.jpg — supplied numbered worksheet map
- .nojekyll — GitHub Pages configuration
- README.md — these instructions
- CREDITS.md — map attribution and regional classification

You can also open index.html directly in a browser after extracting all the files into the same folder.

## Updates and troubleshooting

Edit and commit files on main to update the published game. Refresh the game after publication; use Ctrl+F5 if your browser still shows an old version.

- **404:** Confirm Pages is set to main and /(root), and index.html is at the top level.
- **Missing map:** Confirm classroom-map.jpg is alongside index.html with exactly that spelling and capitalization.
- **Buttons do not work:** Confirm game.js is alongside index.html.
- **Publication not ready:** Check the repository's Actions tab for the Pages build result.
- **School filter blocks the site:** Ask your district to allow the published GitHub Pages address.

This package is ready to upload; it does not create a repository or enable Pages automatically.
