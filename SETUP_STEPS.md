# Setting up your site on GitHub Pages (about 20 minutes, no software to install)

## 1. Create a GitHub account
Go to https://github.com/signup. Choose a username you'd like in your web address — the site
will live at https://USERNAME.github.io (e.g. "aileennielsen" -> https://aileennielsen.github.io).

## 2. Create the repository
- Click the "+" (top right) -> "New repository".
- Repository name: exactly  USERNAME.github.io  (replace USERNAME with your username).
- Public. Leave "Add a README" unchecked. Click "Create repository".

## 3. Upload these files
- On the new empty repository page click "uploading an existing file".
- Drag ALL of the files from this folder into the browser window
  (_config.yml, index.md, about.md, research.md, teaching.md, cv.md, and the assets folder).
- Scroll down and click "Commit changes".

## 4. Turn on GitHub Pages
- In the repository click "Settings" -> "Pages" (left menu).
- Under "Build and deployment", Source = "Deploy from a branch"; Branch = "main", folder "/ (root)". Save.
- Wait 1–2 minutes, then open https://USERNAME.github.io.

## 5. Add your photo and CV

## 6. Editing later (the easy part)
- Click any .md file, click the pencil icon, edit the text, click "Commit changes".
- The site rebuilds itself in about a minute. That's it.
- index.md = News (landing page), about.md = About/bio, research.md = publications, teaching.md = courses, cv.md = CV.
- _config.yml = site title, tagline, and which pages appear in the top menu.

## 7. Link it from UMass
Submit the URL through the UMass directory edit-request form
(https://www.umassd.edu/directory/edit-requests/) and ask for it to be added to your faculty profile.

## Optional: your own domain (e.g. aileennielsen.com)
Buy the domain (Namecheap or Cloudflare, about $12/year). In the repository: Settings -> Pages ->
Custom domain -> enter the domain and save. At your domain registrar add these DNS records:
  A records for "@" pointing to 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
  CNAME record for "www" pointing to USERNAME.github.io
Then tick "Enforce HTTPS" in Settings -> Pages once it becomes available (up to 24 h).
