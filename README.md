# Plauderstunde

A German speaking tutor that runs in the browser. Lotte plays a scene with you at your level (A1–C2), answers aloud in German and marks your mistakes below in red pen. The app also has new words, idioms and slang, saved phrases with flashcards, and progress tracking for each person.

The app is one HTML page. It talks directly to Google Gemini (free key) or Anthropic Claude (paid key). There is no server, and your key and your progress stay on your device.

## Put it online with GitHub Pages (about 5 minutes)

1. Sign in at [github.com](https://github.com). A free account is enough.
2. Click **+** (top right) → **New repository**.
   - Repository name: `plauderstunde`
   - Visibility: **Public**. Free GitHub Pages needs a public repo, but only the app code is public. Your key and progress never go to GitHub.
   - Do **not** tick "Add a README file".
   - Click **Create repository**.
3. On the empty repository page, click the link **uploading an existing file**.
4. Open the unzipped folder, select **all files inside it** (index.html, manifest.webmanifest, the three icon-*.png files and this README.md), and drag them into the browser window. Drag the files themselves, not the folder.
5. Click **Commit changes**.
6. Open the repository's **Settings** tab → **Pages** (left sidebar).
   - Under *Build and deployment* → *Source*, choose **Deploy from a branch**.
   - Branch: **main**, folder: **/ (root)** → **Save**.
7. Wait 1–2 minutes and refresh the page. It shows **"Your site is live at https://YOUR-USERNAME.github.io/plauderstunde/"**.

## First start on your iPhone

1. Open that address in **Safari**.
2. Tap **Jetzt einrichten** and follow the three steps:
   - Open [aistudio.google.com/apikey](https://aistudio.google.com/apikey) and sign in with Google.
   - Tap **Create API key** and copy it.
   - Paste it into the app and tap **Speichern & prüfen**.
3. Tap **Share** → **Add to Home Screen** → **Add**. You now have a Plauderstunde icon.

## Good to know

- **Speaking:** In a Safari tab, the round mic button works (Siri & Dictation must be on). In the Home Screen app, Apple doesn't allow it, so tap the text box and use the mic on your keyboard.
- **Your progress** is saved in the browser on this device. Use the Home Screen icon: Safari can clear data from websites you haven't opened for 7 days, but Home Screen apps are exempt. Use **Einstellungen → Sicherung speichern** now and then. You can load that file on another device too.
- **Profiles:** in Einstellungen, add one profile per person. Each has its own level, saved phrases and progress.
- **Free Gemini limits:** Google doesn't publish exact numbers. Flash-Lite models allow several hundred messages a day; Flash models give sharper corrections but only a few free messages. If a limit is hit, Lotte switches model automatically. Daily limits reset around 9:00 German time.
- **Privacy:** on Google's free tier, what you type may be used to improve Google's products. Don't share private details with Lotte. With a paid Claude key this doesn't apply.
- **Updating the app:** in the repository click **Add file → Upload files**, upload the new `index.html`, and commit. The site updates within a minute and your progress stays.
