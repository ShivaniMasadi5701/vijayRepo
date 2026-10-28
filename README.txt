KnowYourFounder interactive poster package
===========================================

FILES
- index.html            The webpage and clickable image map.
- KnowYourFounder.png   Sample poster image. Replace this with your actual poster.

HOW TO TEST LOCALLY
1. Keep index.html and KnowYourFounder.png in the same folder.
2. Replace KnowYourFounder.png with your poster image. Keep the exact filename, or update src in index.html.
3. Double-click index.html to open it in your browser.
4. Click the poster sections to test their links.
5. The image-map coordinates in index.html are examples for a 928 x 1600 image. If your poster's layout differs, adjust the coords values for each area.

BEFORE HOSTING / WHATSAPP SHARING
1. Upload both files to the same public website folder.
2. In index.html, replace:
   https://YOUR-DOMAIN.example/KnowYourFounder.png
   https://YOUR-DOMAIN.example/
   with the actual public HTTPS image URL and page URL.
3. Keep the poster image publicly accessible. Social preview bots must be able to fetch it without logging in.
4. Share the public webpage URL in WhatsApp. WhatsApp may cache previews, so preview updates can take time.
5. The WhatsApp preview image itself is not clickable by section. People tap the preview/link to open the webpage, then use the clickable areas on the webpage.

LINKS
All poster sections currently link to the KnowYourFounder homepage, except Explore Now, which links to /start.html. Edit href values in index.html if you have specific destination pages.

NOTE
The responsive image-map library is loaded from a CDN, so an internet connection is needed for responsive clickable regions. The image and HTML themselves can be opened locally.
