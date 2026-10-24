# Birthday Wish for Her

A 12-slide interactive birthday story (plus a setup page).

## Run it
Open `index.html` in any browser.

## Embed her photos directly in index.html
1. Copy her photos into the `photos` folder (about 800 px wide is plenty).
2. Open `index.html` in a text editor. At the top of the script you will see:

       var EMBED_M=[];   // memory photos
       var EMBED_B=[];   // balloon photos (up to 6)

3. List the files, in the order you want them:

       var EMBED_M=['photos/m1.jpg','photos/m2.jpg','photos/m3.jpg'];
       var EMBED_B=['photos/b1.jpg','photos/b2.jpg','photos/b3.jpg','photos/b4.jpg','photos/b5.jpg','photos/b6.jpg'];

Memory photo 1 goes with memory line 1, and so on. Balloon photo 1 goes on balloon 1.
Everyone who opens the page sees these photos, with no upload needed.

## Put it online with GitHub Pages
1. Create a repository (for example `birthday-wish`).
2. Upload `index.html`, `README.md` and the whole `photos` folder.
3. Settings > Pages > choose the `main` branch and `/ (root)` > Save.
4. Your link: `https://YOUR-USERNAME.github.io/birthday-wish/`

## Direct link (skips the setup page)
Open your page, fill in her name and details, tap "Create direct link", and add the
ending that starts with `#d.` to your page link:
`https://YOUR-USERNAME.github.io/birthday-wish/#d.…`
Embedded photos still show, because they are part of the page itself.

Name only: `https://YOUR-USERNAME.github.io/birthday-wish/#Priya`
