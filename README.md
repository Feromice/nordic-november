# Nordic November

A single-page trip guide for 17–29 Nov 2026: Oslo, Tromsø, Rovaniemi, Helsinki and a Black Friday trip to Sweden. It has day-by-day plans with transport, bad-weather and toddler plan Bs, and packing lists.

Everything lives in `index.html`, with no build step. Fonts load from Google Fonts and fall back to system fonts when you're offline.

## Publish with GitHub Pages

1. Open the repository on GitHub and go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
3. Pick branch **main** and folder **/ (root)**, then click **Save**.
4. After a minute or two the page is live at `https://<your-username>.github.io/nordic-november/`.

## Update the plan

Edit `index.html` and commit to `main`. Pages republishes on its own. The itinerary is in the `DAYS` array and the packing list is in the `PACK` array, both inside the `<script>` block.

The page is public, so keep personal names, booking references and seat numbers out of it.
