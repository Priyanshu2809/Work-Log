# Strata Work Log

A free app for logging building maintenance work, photos and paint records, and sending reports to the strata council.

- Works **offline**. Everything is saved on your phone.
- **No account, no subscription, no ads.**
- Free hosting on **GitHub Pages**.

---

## Put it online with GitHub (one time, about 10 minutes)

1. Create a free account at **github.com**.
2. Click **+** (top right) → **New repository**.
   - Name: `work-log`
   - Choose **Public** (free GitHub Pages needs a public repository; your *data* is never uploaded, only the app files).
   - Click **Create repository**.
3. Click **uploading an existing file**, then drag in **all 8 files** from this folder:
   `index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`,
   `jspdf.umd.min.js`, `jspdf.plugin.autotable.min.js`, `README.md`
   Click **Commit changes**.
4. Go to **Settings** → **Pages**.
   - Source: **Deploy from a branch**
   - Branch: **main**, folder **/ (root)** → **Save**
5. Wait 1–2 minutes. Your app address will be:
   `https://YOUR-GITHUB-NAME.github.io/work-log/`

## Install it on your phone

**iPhone (Safari):** open your app address → tap **Share** → **Add to Home Screen**.
**Android (Chrome):** open your app address → tap **⋮** → **Add to Home screen** / **Install app**.

Open it once while online. After that it works with no internet.

## How to use it

| Tab | What it's for |
|---|---|
| **Home** | Big **+ Log a job** button, quick-pick jobs, checks due today, jobs waiting on council |
| **Jobs** | Every job, with search and filters |
| **Checks** | Your daily / weekly / monthly rounds. Tap ✓ when done; it's logged automatically. Tap **Issue** if you find a problem |
| **Send** | Weekly or monthly report for council, sent as a **PDF with photos** |
| **More** | Paint records, your details, backup |

### Sending updates to council
- **One job** (e.g. you need approval for a quote): open the job → **📤 Save & send to council**. Your phone asks which app to use (Mail, Gmail, WhatsApp, Messages); the message and photos are already filled in.
- **Weekly report:** **Send** tab → **📤 Send report to council (PDF)**. Choose Mail and send.
- On a computer, the PDF downloads and an email draft opens. Attach the PDF and send.

### ✨ Smart writing (works offline, no subscription)
- **Quick notes → jobs** (Home): type or speak rough notes, one job per line, e.g. `fixd lobby door closser 15 min` or `replaced 2 lts 5th flr hw $8`. The app fixes spelling and short forms, writes a clean title, and finds the area, category, status, time and cost. Check the preview, then save.
- **✨ Tidy up my notes** (inside any job): turns rough notes into clean text and fills in the details.
- **Auto summary:** every report starts with a written summary of your period (jobs done, checks done, areas covered, issues found, next steps).
- **Optional polish:** on the Send tab, **Copy for Claude / ChatGPT** copies your report with instructions to make it more polished, without adding anything that didn't happen. Paste it into the free version of either app.

### 💡 Quiet days
On a slow day, Home shows useful preventive jobs (touch-ups, tightening hardware, checking exit signs…). Do one, then tap it to log it.

### Weekly routine
1. Log jobs as you do them, with before/after photos (🎤 use voice typing for notes).
2. Tick off your checks.
3. Friday: **Send** → send the report.
4. When the yellow banner asks, tap **Back up** and save the file to Google Drive or iCloud.

## Important: your data

- Your jobs and photos are stored **only on this phone, in this browser**. They are not uploaded anywhere.
- If you delete the browser's data, change phones, or uninstall the app, the data is gone, **unless you have a backup**.
- To move to a new phone: download a backup on the old phone → install the app on the new phone → **Me** → **Restore backup**.

## Updating the app

Upload the new `index.html` (and `sw.js` if it changed) to the same GitHub repository. Your saved data stays on your phone and is not affected.
