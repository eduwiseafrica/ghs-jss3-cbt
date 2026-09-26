# Grace Heritage Schools — JSS3 CBT (English Language & Civic Education)

This package contains one file: **index.html** — the complete, self-contained
CBT tool. It has no external dependencies (no internet calls, no fonts, no
scripts loaded from elsewhere), so once it's hosted or downloaded, it runs
entirely on its own.

You only need to do ONE of the two options below — pick whichever suits you.

---

## Option A — Get a free public link in under a minute (Netlify Drop)

Best if you just want a URL to send to students right now, no account needed.

1. On your computer, open a browser and go to: **https://app.netlify.com/drop**
2. Drag the **index.html** file straight onto that page (drag the whole
   folder, or just the file — either works).
3. Netlify instantly gives you a live link that looks like:
   `https://random-name-123.netlify.app`
4. Copy that link and send it to your students. It opens directly in any
   phone or computer browser — no sign-up, no Claude account, no prompts.
5. (Optional, later) If you ever want to claim the site under your own
   Netlify account so it doesn't get cleaned up after long inactivity, you
   can sign up for free and click "Claim this site" from the same page —
   but this is optional, not required to get the link working today.

---

## Option B — A permanent link you fully own (GitHub Pages)

Best if you want a stable, long-term link tied to your own account.

1. Go to **https://github.com** and sign in (create a free account if you
   don't have one).
2. Click the **+** icon (top right) → **New repository**.
   - Name it anything, e.g. `ghs-jss3-cbt`.
   - Set it to **Public**.
   - Click **Create repository**.
3. On the new repository page, click **"Add file" → "Upload files"**.
4. Drag in the **index.html** file from this package, then click
   **Commit changes**.
5. Go to the repository's **Settings** tab → **Pages** (left sidebar).
6. Under **Build and deployment → Source**, choose **Deploy from a branch**,
   set Branch to **main** and folder to **/ (root)**, then **Save**.
7. Wait about a minute, then refresh the Pages settings page — GitHub will
   show your live link, something like:
   `https://your-username.github.io/ghs-jss3-cbt/`
8. Share that link with students. It stays online for free, permanently,
   under your own GitHub account.

---

## Important notes for exam day

- Each student's answers and timer are saved **in their own browser only**
  (using local storage on their device) — nobody else can see another
  student's answers, and you (or Netlify/GitHub) cannot see their answers
  either. There is no central record of scores; students see their own
  result on their own screen at the end.
- If a student's browser or tab is closed mid-test, reopening the same link
  on the same device will resume that subject with the timer continuing
  correctly from where it left off.
- If a student clears their browser data/history, their in-progress attempt
  on that device will be lost — advise them not to do this during the test.
- The file works fully offline after it has loaded once on a device, so a
  shaky school Wi-Fi will not interrupt a test already in progress.
