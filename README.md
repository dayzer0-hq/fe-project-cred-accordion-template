# CRED — FAQ accordion (JavaScript)

Welcome. This repository is **empty on purpose**. Everything in it is yours to create.

## Where the work is

Open the **Issues** tab. There are four, in order. Each one says exactly what done looks like.

One issue at a time:

```bash
git checkout main
git pull
git checkout -b issue-1
# ...make your changes...
git add .
git commit -m "Add the accordion markup"
git push -u origin issue-1
```

Then open a **Pull Request** with `Closes #1` in the description. Raj reviews it. Approved
means it merges itself; changes requested means push again to the **same branch**.

## What you need installed

Nothing. A text editor and a browser. Open your `.html` file directly — there is no server to
start and no build step, so an address bar beginning `file://` is correct.

You will want the browser's developer tools open while you work on this one. `Console` is where
your JavaScript errors appear, and if a click does nothing at all, that panel is the first place
to look rather than the last.

## A note on this project

This is the first project on the beginner shelf with **JavaScript** in it. No framework and no
library — no React, no jQuery, no Bootstrap. Plain `addEventListener` and plain DOM.

Two things are worth knowing before you start. An accordion that opens and closes is only half
of it: the other half is that somebody using a keyboard or a screen reader can tell which panel
is open, which is what `aria-expanded` is for. And an accordion is a piece of **state** — which
panel is open right now — so the interesting question is not "how do I hide a div" but "where
does that answer live".

Ask Priya on Slack if anything is unclear; that is what she is there for.
