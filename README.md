# savarsuri-site

My personal site. An operations console rather than a portfolio page, because a list of links felt like the wrong shape for what I actually do.

**Live:** [savarsuri-site.vercel.app](https://savarsuri-site.vercel.app)

---

## What it is

One self-contained HTML file. No framework, no build step, no dependencies. Six views behind a tab bar:

| View | What's in it |
|---|---|
| Overview | Who I am and what I'm working toward, in one screen |
| Systems | Projects, what they do, what broke, what I fixed |
| Record | Coursework and academic detail |
| Credentials | Certifications, earned and in progress, with dates |
| Stack | Languages, tools, platforms |
| Contact | How to reach me |

Plus a live clock, animated counters, progress meters on the in-progress certifications, and an activity log.

## Why one file

I wanted to understand every line on the page. A framework would have given me a faster start and a worse understanding, and the site is small enough that the tradeoff isn't close. Everything is hand-written: the tab routing, the URL hash sync, the counter animation, the theme toggle.

## Details worth noting

- **URL hash routing.** Each tab has its own hash, so a view is linkable and the back button works.
- **Keyboard navigation.** Arrow keys move between tabs. Focus states are visible.
- **Dark and light.** Both are designed, not one inverted. The toggle respects the system preference on first load.
- **No tracking.** No analytics and no third-party scripts. The only outside request is the Google Fonts stylesheet.
- **Responsive to phone width** with no horizontal scroll.

## Stack

Plain HTML, CSS, and JavaScript. Deployed on Vercel from this repo, so a push to `main` ships it.

## Running it

Clone and open `index.html`. That's the whole setup.

## License

MIT
