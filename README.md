# Tide Readers Hub

This is the team page at **https://hub.tidereaders.org**.

You only ever edit one file: **hub.md**. Please leave the other files alone.

## How to edit the page

### 1. Accept the GitHub invite

You'll get an email from GitHub saying you've been invited to collaborate on **tide-readers/hub**. Click **View invitation**, then **Accept invitation**.

- No email? Sign in to GitHub and go to https://github.com/tide-readers/hub/invitations
- No GitHub account yet? Create a free one at https://github.com/signup and post your username in Slack so you can be invited.

### 2. Open hub.md and click the pencil

Go to https://github.com/tide-readers/hub/blob/main/hub.md and click the **pencil icon** (Edit this file) at the top right of the file.

Shortcut: the **Edit this page** button on hub.tidereaders.org takes you straight there.

### 3. Make your edit

Type in the box. The page uses Markdown, which is just a few symbols for formatting:

| To get | Type this |
|---|---|
| A heading | `## Next steps` |
| A bullet point | `- Book the room` |
| A checkbox | `- [ ] Book the room` |
| A ticked checkbox | `- [x] Book the room` |
| A link | `[OceanX](https://oceanx.org)` |
| Bold text | `**important**` |

Tips:

- Leave an empty line between paragraphs, and before a list or a heading.
- Every `##` heading becomes its own box on the page.
- Click **Preview** at the top of the box to see how it will look before you save.
- Getting help from Claude or another assistant? Ask it for the finished Markdown, paste it into the box, and check **Preview** before you save.

### 4. Click "Commit changes"

Click the green **Commit changes…** button. Write a short note about what you changed, for example *Added interview dates*. Keep **Commit directly to the main branch** selected, then click **Commit changes** again.

### 5. Check the page

The page at https://hub.tidereaders.org updates within about a minute. Refresh it to see your change. The top of the page shows who edited it last.

## If two people edit at the same time

If someone else saved hub.md while you were editing, GitHub may show a conflict and not save your edit. Nothing on the page is broken.

1. Copy your text somewhere safe first (select all, copy).
2. Post in Slack that you hit a conflict.
3. Sort it out together: open hub.md again, so you start from the latest version, and add your change back in.

## Made a mistake?

Every saved edit is kept. Click **History** at the top of hub.md (or **Past edits** at the bottom of the page) to see earlier versions. Post in Slack and someone can bring an old version back.

## For whoever maintains this

- `index.html` fetches `hub.md`, turns it into HTML with marked, cleans it with DOMPurify, and shows the latest edit from the GitHub API. There's no build step.
- Hosted on Vercel in the Tide Readers team. Every commit to `main` deploys automatically.
- Keep this repository **public**. Vercel's free Hobby plan only deploys collaborators' commits from public repositories.
