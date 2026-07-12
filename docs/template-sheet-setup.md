# Template Form + Settings sheet (operator setup)

This documents the template contents, for anyone who prefers building from
scratch or wants to know what the templates contain.

> Copy the templates directly:
> **[Template Form](https://docs.google.com/forms/d/17q-DL4U1WSOZMjLW-1eFvITgf3WCB2dZmNdtcMeoSps/copy)** ·
> **[Template Settings sheet](https://docs.google.com/spreadsheets/d/1ERtFGoGEOolNR0qk1G7O0xisJzjbQKsIxeCfuum0R64/copy)**
> (each link opens a "Make a copy" prompt; sign in to Google if asked)

## Why two documents

The board reads two published-CSV URLs that do NOT need to come from the same
spreadsheet. That sidesteps the classic Google gotcha: copying a Sheet does
not bring its linked Form along. So the flow is: copy the Form (it creates
its own response spreadsheet), copy the Settings sheet separately.

## The Form (template contents)

Title: "Progress Update"

(The form title is cosmetic; the board never reads it. Only the question
wordings matter, since they become the board's column headers. Operators
running monthly or quarterly cadences just set the "Count since" row
accordingly.)

1. **Your name (or your company's name — whatever you prefer)**
   Short answer. Required.
   (This wording matters: it lets people in privacy-sensitive programs use a
   company name or handle instead of a real name.)
2. **📞 Outreach made (enter a number)**
   Short answer, number validation.
   Description: "Any direct attempt to contact a potential customer or
   stakeholder: DMs, emails, cold calls."
3. **💰 Revenue closed (enter a number)**
   Short answer, number validation.
   Description: "Deals that have officially closed. Dollars, not promises."

Rename, add, or remove metric questions freely; every question after the
name becomes its own leaderboard column. Keep "name" in the name question's
wording (the board finds the team column by it). Put "revenue", "sales",
"earner", or "$" in money questions so they format as currency.

## The Settings sheet (template contents)

Named format: column A names the setting, column B holds the value, column C
is a human note. The board matches rows by the name in column A and ignores
anything it doesn't recognize (the header row, the "Your board link" row,
blank rows), so copiers can't break it by rearranging.

Exact template cells (row 1 is a header; style it bold, and consider light
gray + italic for column C):

| A | B | C |
|---|---|---|
| What it controls | 👉 Your input (edit this column) | Notes |
| Title | My Program Leaderboard | The big headline on the board |
| Date range | Week 1 of 8 | Shows in the subtitle |
| Explainer | Resets every Monday at midnight | Shows after the date |
| Disclaimer | Disclaimer: All numbers are self-reported. The point of this leaderboard is motivation and community. Awards and recognition are at the discretion of the program organizers. | Small print in the footer |
| Powered by text | | Blank shows a small "Made with Cohort Leaderboard" credit |
| Powered by URL | | Where your powered-by text/logo links |
| Submit button text | Submit Updates | The button founders click to open your form |
| Submit button URL | | Paste YOUR copied Form's share link here |
| Show score gap | OFF | ON shows "X behind" under each score |
| Stack on mobile | ON | One column on phones |
| Multiple submissions | SUM | SUM adds them up; LATEST keeps newest; MAX keeps best; blank shows every submission |
| Logo URL | | Optional footer logo image |
| Count since | | e.g. 12/8/2025 — older submissions are ignored; change it each week for resets |
| Your board link | | Not a setting. After you build your board, paste its link here so you never lose it |

Template default for Multiple submissions is SUM, so founders can submit as
often as they like and duplicate rows never appear.

Recommended extra: a hover note on B2 (right-click > Insert note):
"Replace with your program's name. Everything in this column is yours to
edit." Notes never appear in the published CSV.

## Operator steps (what the copy flow looks like)

1. Click the **Template Form copy link** above → Make a copy.
2. In your copy, click **Publish** (top right; keep "anyone with the link"
   as responders). Copies arrive unpublished, and founders can't submit
   until you do this.
3. Responses tab → **Link to Sheets** → creates your response spreadsheet.
3. Click the **Template Settings sheet copy link** above → Make a copy.
4. Edit your Settings copy: title, dates, and paste your Form's "Send" link
   into the "Submit button URL" row.
5. Publish both as CSV (File > Share > Publish to web; pick the
   Form-responses tab in one, Settings in the other; format = .csv).
6. Paste the two URLs into the leaderboard builder. Done.

## Testing checklist (before sharing template links publicly)

- [ ] Copy the Form from a DIFFERENT Google account than the one that owns it.
- [ ] Link responses, submit one test entry, confirm it lands.
- [ ] Copy the Settings sheet from the other account.
- [ ] Publish both, build a board, confirm title + entry render.
- [ ] Confirm the Submit button opens the copied Form (not the template).
