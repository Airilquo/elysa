GOLDEN HOUR - how to put it online

1. Put your photos, videos and song in the media folder (see media/README.txt for names).
2. Upload the WHOLE folder (index.html + media) to any static host:
   - Netlify Drop: go to app.netlify.com/drop and drag the folder in. Easiest.
   - Cloudflare Pages: Create project > Direct Upload > upload the folder.
   - Vercel or GitHub Pages also work.
3. Open the link on your phone and test everything before sending it to her.

To change her name or birthday, open index.html in a text editor and search for:
  var defaults={name:'Elysa'
