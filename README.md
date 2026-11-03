# OceanX Research Hub

This is the team site at **https://hub.tidereaders.org**.

You only ever edit one file: **hub.md**. It holds every entry in the **Research library**. Please leave the other files alone.

## How to edit the library

### 1. Accept the GitHub invite

You'll get an email from GitHub saying you've been invited to collaborate on **tide-readers/hub**. Click **View invitation**, then **Accept invitation**.

- No email? Sign in to GitHub and go to https://github.com/tide-readers/hub/invitations
- No GitHub account yet? Create a free one at https://github.com/signup and post your username in Slack so you can be invited.

### 2. Open hub.md and click the pencil

Go to https://github.com/tide-readers/hub/blob/main/hub.md and click the **pencil icon** (Edit this file) at the top right of the file.

Shortcut: the **Edit the library** button at the bottom of hub.tidereaders.org takes you straight there.

### 3. Make your edit

hub.md is split into topics and entries:

- A line starting with `##` is a **topic**. Topics become the filter buttons in the library.
- A line starting with `###` is one **entry**.
- Under an entry, write one summary sentence, then bullet points, then a `Source:` line.
- `Confidence:`, `Link:` and `Added by:` lines are optional. `Added by:` shows your name as a tag on the entry.

To add an entry, copy this under the right topic and fill it in:

```
### Title of the entry

One sentence that sums it up.

- First point
- Second point

Source: Where it comes from
Link: https://example.com
Added by: Your name
```

The rest is Markdown, which is just a few symbols for formatting:

| To get | Type this |
|---|---|
| A heading | `## New topic` or `### New entry` |
| A bullet point | `- Book the room` |
| A checkbox | `- [ ] Book the room` |
| A ticked checkbox | `- [x] Book the room` |
| A link | `[OceanX](https://oceanx.org)` |
| Bold text | `**important**` |

Tips:

- Leave an empty line between the summary, the bullet list and the `Source:` line.
- To move an entry to another topic, cut it and paste it under that topic's `##` heading.
- Click **Preview** at the top of the box to check it before you save.
- Getting help from Claude or another assistant? Ask it for the finished Markdown in the format above, paste it into the box, and check **Preview** before you save.

### 4. Click "Commit changes"

Click the green **Commit changes…** button. Write a short note about what you changed, for example *Added interview notes*. Keep **Commit directly to the main branch** selected, then click **Commit changes** again.

### 5. Check the page

The site at https://hub.tidereaders.org updates within about a minute. Refresh it and open **Research library** to see your change. The library shows who edited it last.

## If two people edit at the same time

If someone else saved hub.md while you were editing, GitHub may show a conflict and not save your edit. Nothing on the site is broken.

1. Copy your text somewhere safe first (select all, copy).
2. Post in Slack that you hit a conflict.
3. Sort it out together: open hub.md again, so you start from the latest version, and add your change back in.

## Made a mistake?

Every saved edit is kept. Click **History** at the top of hub.md to see earlier versions. Post in Slack and someone can bring an old version back.

## Changing the other pages

The Overview, Key takeaways and Recommendation pages are written into `index.html`, not hub.md. Post in Slack if something there needs changing.

## For whoever maintains this

- `index.html` is the OceanX Research Hub page. Its library reads `hub.md`, parses it with marked, cleans the result with DOMPurify, and shows the latest edit from the GitHub API. There's no build step.
- Hosted on Vercel in the Tide Readers team. Every commit to `main` deploys automatically.
- Keep this repository **public**. Vercel's free Hobby plan only deploys collaborators' commits from public repositories.
