# Commercial Readiness Weekly Status Report

## Week of 8/26 – 9/2

### Summary
_Not yet entered — fill in via `index.html`._

### Active Projects

**Physician and Pharmacist Initiatives**
- ClinicalKey Unified Vision (CK+?): No updates
- ClinicalKey for Nursing Unified Vision (CKN+?): No updates
- ClinicalKey (CK) Physician BAU: No updates
- CK AI BAU: No updates
- CPCK BAU: No updates
- CK for Medical Schools BAU: No updates
- CK Test Prep BAU: No updates
- NEOID LMS Access CK Student: No updates

**Nursing and Patient Education Initiatives**
- Clinical Learning Hub: No updates
- CK Student NOAM/Clinical Cases BAU: No updates
- CK Nursing BAU: No updates
- Patient Pass/PE Products BAU: No updates
- Clinical eLearning BAU: No updates

**Specialist Solution Initiatives**
- ClinicalPath BAU: No updates
- ClinicalPath Provider Reports: No updates
- PSS BAU: No updates

**Strategic/Corporate Initiatives**
- eLearning Localization: No updates

**Miscellaneous**
- Project Phoenix Admin Console: No updates

**Other / Miscellaneous:** _Not yet entered._

### Out of Office
- Kelly: None
- Barry: None
- Tessa: None
- Laura: None
- Andrew: None
- Jan: None

### Recognition
_Not yet entered._

### Sign Off
- [ ] Kelly — not yet signed
- [ ] Barry — not yet signed
- [ ] Tessa — not yet signed
- [ ] Laura — not yet signed
- [ ] Andrew — not yet signed
- [ ] Jan — not yet signed

---

> The section above reflects the current, unfilled draft state of `index.html`. Fill out the form there, and once everyone has signed off, replace this block with the output of **Download Markdown** so this README always shows the latest completed report.

## About this repo

A fillable version of the Commercial Readiness Weekly Status Report, organized around the team's active projects. This is a separate repo/site from the CLH Weekly Status report.

Closed, cancelled, and paused initiatives from the source report aren't listed individually — anything outside the active project list (e.g. Gong, CS Customer Centric Standup, ADA file conversion) goes in the **Other / Miscellaneous** field.

## Using it

Open `index.html` in a browser (or the published GitHub Pages link). No install, no login.

- **Week of** — the two date fields at the top control which draft is loaded/saved. Changing them switches to that week's draft.
- **Summary** — the one mandatory highlight bullet for the week.
- **Active Projects** — one row per currently active initiative, grouped the same way as the source report. Each row has an **Update this week?** dropdown:
  - **No updates** (default) — nothing more to do for that project.
  - **Yes — add update** — reveals a text box below the row to fill in.
  - A row with an update is highlighted so it's easy to see what's changed at a glance.
- **Other / Miscellaneous** — a catch-all for anything that isn't tied to one of the listed active projects.
- **Out of Office** — a line per team member for planned time out this week; leave blank if none.
- **Recognition** — free text, per the report's own rule to recognize at least one teammate each week.
- **Sign Off** — each of the six names (Kelly, Barry, Tessa, Laura, Andrew, Jan) has a checkbox. Checking it records that person's sign-off with a timestamp. The counter above shows how many of 6 have signed.

### Turning entries into a viewable report

Click **View Report** (top or bottom of the page) at any point to see everything you've entered rendered as a clean, read-only report — no downloading or printing required. It updates live from whatever is currently filled in, including partial/in-progress entries and sign-off status. Use **← Back to Edit** to return to the form. From the report view you can also jump straight to **Download Markdown** or **Print / Export PDF** without going back to the form first.

### Saving your work

The page autosaves to your browser's local storage as you type (per week), so refreshing or closing the tab won't lose progress. **Save Draft** saves immediately and shows a timestamp; **Clear Draft** wipes the current week's saved data.

Autosave is per-browser, not shared — it protects your own in-progress edits, not a sync between teammates. Whoever is the primary editor each week should be the one filling this in and exporting it.

### Publishing the finished report

Once everyone has signed off:

1. Open **View Report** to do a final read-through.
2. Click **Download Markdown** to generate a `.md` file of the completed report (summary, project updates, OoO, recognition, and sign-offs).
3. Replace the report block at the top of this README with that content (or commit it to a `/reports` folder, e.g. `reports/2026-08-26_to_2026-09-02.md`, for a running archive) — a version-controlled record replacing the separate Word docs.
4. Alternatively, use **Print / Export PDF** for a clean, form-free printable version.

## Updating the active project list

The active projects are hardcoded in `index.html` in the `ACTIVE_PROJECTS` array near the top of the `<script>` block, grouped exactly like the source report's categories. When a project closes, is cancelled, is added, or a paused project resumes, edit that array directly (add/remove a string from the relevant category's `items` list).

## Publishing with GitHub Pages

1. Push this folder to GitHub.
2. **Settings → Pages** → set **Source** to "Deploy from a branch," branch `main`, folder `/ (root)` (or wherever this folder lives in the repo).
3. GitHub publishes it at `https://<your-username>.github.io/<repo-name>/`.

## Files

- `index.html` — the fillable report, including the View Report screen.
- `README.md` — this file (current report + usage instructions).
