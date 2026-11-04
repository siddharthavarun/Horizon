# Financial Planner 2027

A personal financial planner that runs as an app on your iPhone. Your figures are stored only on the device you enter them on. Nothing is sent to a server.

## 1. Put it on GitHub Pages (once, about 5 minutes, on your laptop)

1. Sign in at github.com and click **New repository**.
2. Name it `planner-2027`, choose **Public**, and click **Create repository**. Free GitHub Pages needs a public repository. That's fine here: the code holds none of your figures.
3. On the new repository page, click **uploading an existing file**.
4. Unzip this folder and drag in everything inside it: `index.html`, `manifest.webmanifest`, `sw.js`, `README.md` and the `icons` folder. Click **Commit changes**.
5. Go to **Settings → Pages**. Under *Build and deployment*, set **Source** to *Deploy from a branch*, choose **main** and **/ (root)**, then click **Save**.
6. After a minute or two the page shows your address, for example `https://YOUR-USERNAME.github.io/planner-2027/`.

## 2. Install it on your iPhone

1. Open that address in **Safari**. It has to be Safari for the install to work.
2. Tap **Share**, then **Add to Home Screen**, then **Add**.
3. Open **Planner 27** from your Home Screen. It opens full screen like an app and works offline.

Enter your figures in the Home Screen app itself. On iPhone, the Home Screen app and a Safari tab keep separate storage, so figures typed in Safari won't show up in the app.

## 3. Keep your figures safe

- Everything is saved automatically on the phone.
- Go to **Settings → Export backup** now and then, and save the file to Files or iCloud Drive.
- If you delete the app or get a new phone, install it again and use **Settings → Import backup**.
- To use the same figures on your laptop, export on one device and import on the other. The two don't sync by themselves.
- Never upload a backup file to the GitHub repository. Anyone can see public repositories.

## Updating the app later

Upload the new `index.html` to the repository in the same way, then open `sw.js` and change `planner-2027-v1` to `planner-2027-v2` so phones load the new version. Close and reopen the app twice to see the update. Your figures are not affected.
