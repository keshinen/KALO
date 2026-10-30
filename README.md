# Hahahaha

A one-page prank site. It looks like a "launching soon" page with a progress bar that crawls to 99%, then flips to a big "HAHAHAHAHA" and tells the visitor: *you really thought we had time to make a website.*

- Single file, no build step, no dependencies
- Works on phones and laptops
- Follows light and dark mode
- Fonts load from Google Fonts, with system fallbacks if offline

## Put it online with GitHub Pages

1. Create a new repository on GitHub (for example `hahahaha`).
2. Upload `index.html` and `README.md` to the repository.
3. Go to **Settings**, then **Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Pick the `main` branch and the `/ (root)` folder, then save.
6. After a minute or two, your site is live at `https://YOUR-USERNAME.github.io/hahahaha/`.

Send that link to your victim.

## Tweak it

Open `index.html` and look for:

- `later(9000, reveal)` near the bottom: the number is how many milliseconds before the reveal.
- The `steps` list: the fake loading messages and the percentages they show.
- The `.sub` line in the HTML: the punchline text.
