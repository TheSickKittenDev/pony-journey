# Pony Journey — Netlify Production Publish

## Manual deploy
1. Unzip this archive.
2. Open the `pony_journey_v45` folder.
3. Deploy that folder to Netlify Drop, or use it as the site's publish directory.
4. `netlify.toml` already sets `publish = "."`.
5. Confirm the production `*.netlify.app` URL.
6. Test the PWA install and offline reload on a mobile browser.

## Git deploy
Commit the `pony_journey_v45` directory to a repository and import it into Netlify. No build command is required.

## Important
The browser version and native iOS version share the same game assets. The native shell loads those assets locally; it does not depend on the Netlify URL for gameplay.
