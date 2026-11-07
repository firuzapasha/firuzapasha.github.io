# Firuza Pashazada — Portfolio

Your website plus an admin panel at `/admin`.

## Set up (once, about 10 minutes)

1. **Sign in to GitHub** as `firuzapasha` (or create a free account at github.com).
2. **Create a repository** named exactly `firuzapasha.github.io` and set it to **Public**.
3. **Upload the files.** On the new repository page, click **uploading an existing file**. Drag in everything from this folder: `index.html`, `README.md` and the folders `admin`, `content` and `images`. Click **Commit changes**.
4. **Turn on the website.** Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, then **main** and **/(root)**, and click **Save**. After 1–2 minutes your site is live at **https://firuzapasha.github.io**.
5. **Open the admin panel** at **https://firuzapasha.github.io/admin/** and sign in with an access key:
   - Go to GitHub → Settings → Developer settings → Personal access tokens → **Fine-grained tokens** → **Generate new token** (or open https://github.com/settings/personal-access-tokens/new).
   - Repository access: **Only select repositories** → `firuzapasha.github.io`.
   - Permissions → Repository permissions → **Contents: Read and write**.
   - Generate the key, copy it and paste it into the admin panel. Your browser remembers it.

## Using the admin panel

- **Projects**: the grid shows every project with its cover.
  - Click a project to edit it, or **New project** to add one.
  - **Reorder** changes the order on the site (drag, or use the arrows).
  - **Status → Archived** hides a project without deleting it. **Delete project** removes it.
  - **Show on the home page** puts it in "Selected work".
  - Each project has a cover (upload an image or pick a drawn cover), a short intro, a full text (headings, bold, lists, links) and a gallery.
- **Home page**, **Experience**, **Profile & contact**: every text on the site, plus your photo, email, phone and links.
- **EN / DE** at the top switches which language you are editing. If a German text is empty, the English one is shown on the site.
- Put a word between `*stars*` to make it orange italic.
- Changes are kept in your browser until you click **Publish** in the dark bar at the bottom. The site updates for everyone in about a minute.
- Images are made smaller automatically before uploading.
- Backup editor: **/admin/cms/** (the previous admin panel). It edits the same content.

## Files

- `index.html`: the website (design and animations).
- `content/*.json`: all texts and projects. The admin panel edits these.
- `images/uploads/`: your photo and every image you upload.
- `admin/`: the admin panel. `admin/cms/` is the backup editor (Sveltia CMS).
