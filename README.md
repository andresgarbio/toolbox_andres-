# Toolbox

A multi-language reference toolbox for looking up code fast under time
pressure (CodeSignal GCA and similar). The landing page links to per-language
"dojo" rooms; each room is a single self-contained page with live search and
copy-ready snippets.

## Structure

    index.html          landing hub, links to each language room
    python/index.html   Python Dojo (ready)

Future rooms go in their own folders the same way, for example
`cpp/index.html`, `sql/index.html`. Add a card for each in the `ROOMS` array
near the bottom of the root `index.html`, set `status:"ready"` and an `href`
when the room is live.

## Using a room

Type a keyword to filter the cards live. Search the *symptom* of the problem
("each element points to one other", "shortest path weighted", "unhashable
type"), not just the algorithm name. Every snippet has a copy button.

- `/` focuses the search from anywhere
- `Esc` clears the search

## Run locally

Everything is dependency-free static HTML. Serve the repo root:

    python3 -m http.server 8000

then visit http://localhost:8000

## Host on GitHub Pages

Settings > Pages > Source = Deploy from a branch, `main` / root. The hub goes
live at https://USERNAME.github.io/REPO/ and each room at /python/ and so on.
