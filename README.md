# vipulpatil04.github.io

Personal portfolio — AI infrastructure & storage.

## Publishing this (one time, ~5 minutes)

1. On GitHub, create a **new public repository** named exactly:
   `vipulpatil04.github.io`
   The name must match your username exactly, or GitHub Pages will not serve it at the root domain.
2. Upload every file in this folder to the repo root (drag-and-drop works):
   `index.html`, `about.html`, `projects.html`, `experience.html`,
   `coursework.html`, `style.css`, `Vipul_Patil_Resume.pdf`
3. Go to **Settings → Pages**. Under "Build and deployment", set
   Source = `Deploy from a branch`, Branch = `main`, folder = `/ (root)`. Save.
4. Wait 1–2 minutes. The site is live at **https://vipulpatil04.github.io**

## Updating it later

Edit the HTML file and commit. The site rebuilds automatically within a minute.

## Adding a custom domain later (optional, ~$12/yr)

1. Buy the domain (Namecheap, Cloudflare, Porkbun).
2. In the repo, Settings → Pages → Custom domain → enter it → Save.
3. At your registrar, add these DNS records:
   - Four `A` records for `@` → `185.199.108.153`, `185.199.109.153`,
     `185.199.110.153`, `185.199.111.153`
   - One `CNAME` for `www` → `vipulpatil04.github.io`
4. Tick "Enforce HTTPS" once the certificate is issued.

Nothing in the site code needs to change.

## Adding your photo later

Add `photo.jpg` to this folder, then in `index.html` paste this directly
after the `<h1>Vipul&nbsp;Patil</h1>` line:

    <img src="photo.jpg" alt="Vipul Patil" class="headshot">

and add this to the end of `style.css`:

    .headshot{width:120px;height:120px;border-radius:50%;object-fit:cover;
      border:1px solid var(--line);margin:0 0 20px;display:block;}
