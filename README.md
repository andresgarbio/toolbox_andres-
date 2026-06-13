# GCA Python Reference

A single-page, paste-ready Python reference for timed coding assessments
(CodeSignal GCA and similar). Built for speed of lookup under a running clock.

## Use it

Open the page, type a keyword in the search bar, and the cards filter live.
Search the *symptom* of the problem ("each element points to one other",
"shortest path weighted", "unhashable type"), not just the algorithm name.
Every snippet has a copy button.

- `/` focuses the search from anywhere
- `Esc` clears the search

## What's in it

Medium patterns (two pointers, sliding windows, bisect, binary search on
answer, prefix sums, monotonic stack, intervals, functional-graph cycle
detection), graph algorithms (BFS, DFS, Dijkstra, Kahn topological sort,
union-find), data structures (heapq, LRU cache, iterative segment tree,
trie), DP templates, a stdlib cheat block, and common gotchas.

All snippets use only the Python standard library. No pseudocode.

## Run locally

It is one self-contained file with no dependencies. Open `index.html` in any
browser, or serve it:

    python3 -m http.server 8000

then visit http://localhost:8000

## Host on GitHub Pages

Push this repo, then in Settings > Pages set the source to your main branch
root. The page goes live at https://USERNAME.github.io/REPO/
