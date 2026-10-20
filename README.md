# Daily Hub

One page with three screens:

- **Home**: pick a section, see this week's average weight, an all-time weight graph and a 30-day graph.
- **Schedule**: rolling six-week planner (today plus the next 42 days, moves forward every day). Classes disappear once they start. Edit or add any plan, plus a to-do list and exam countdowns.
- **Weight**: log your morning weight, see the trend, and project it forward for as long as you like.

Everything is saved in the browser. Optional sync through a secret GitHub Gist (see the Sync section on the Home screen).

Single file, no build step. Host it with GitHub Pages.


## Add from a photo

On the Schedule screen, tap **Add from a photo**, pick screenshots or photos of a syllabus, calendar or to-do list, and the app reads the dates and times. You review every item (edit, uncheck, change the date) before anything is added.

- Needs your own Anthropic API key (console.anthropic.com). API use is billed separately from a Claude subscription, so set a spend limit there.
- The key is saved only in this browser. It is never put in your synced data.
- The photos you choose are sent to Anthropic to be read.
- Items on past dates and items already on your schedule start unchecked.
