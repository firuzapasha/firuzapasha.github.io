# Firuza Pashazada — Portfolio

Your website plus an admin panel at `/admin`.

## Set up (once, about 10 minutes)

1. **Sign in to GitHub** as `firuzapasha` (or create a free account at github.com).
2. **Create a repository** named exactly `firuzapasha.github.io` and set it to **Public**.
3. **Upload the files.** On the new repository page, click **uploading an existing file**. Drag in everything from this folder: `index.html`, `README.md` and the folders `admin`, `content` and `images`. Click **Commit changes**.
4. **Turn on the website.** Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, then **main** and **/(root)**, and click **Save**. After 1–2 minutes your site is live at **https://firuzapasha.github.io**.
5. **Open the admin panel** at **https://firuzapasha.github.io/admin/** and click **Sign In Using Access Token**. Then create the token on GitHub:
   - Go to GitHub → Settings → Developer settings → Personal access tokens → **Fine-grained tokens** → **Generate new token**.
   - Repository access: **Only select repositories** → `firuzapasha.github.io`.
   - Permissions → Repository permissions → **Contents: Read and write**.
   - Generate the token, copy it and paste it into the admin panel.
   - Your browser remembers the token, so you only do this once per browser. When it expires, make a new one the same way.

> If your GitHub username or repository name is different, open `admin/config.yml` on GitHub and change the `repo:` and `site_url:` lines.

## Using the admin panel

- **Projects**: add, edit, reorder (drag) and delete projects.
  - To hide a project without deleting it, set **Visibility → Archived**.
  - **Show on home page** puts a project in the "Selected work" section.
  - Each project has its own page, with an intro, a full text (headings, lists, links), a gallery and an optional Behance button.
  - Upload a **Cover image**. If you leave it empty, a drawn cover is used instead.
- **Website texts**: three pages.
  - *Name, photo & contact*: your photo, email, phone and links.
  - *Home page texts*: hero, about, numbers, services and contact heading.
  - *Experience, education, tools & languages*.
- Every text has an **English** and a **Deutsch** box. If you leave a German box empty, the English text is shown.
- Put a word between `*stars*` to make it orange italic. Press Enter in a text box to start a new line.
- Click **Save**. The site updates for everyone within about a minute. If you don't see the change, refresh the page.

## Files

- `index.html`: the website (design and animations).
- `content/*.json`: all texts and projects. The admin panel edits these.
- `images/uploads/`: your photo and every image you upload.
- `admin/`: the admin panel (Sveltia CMS).
