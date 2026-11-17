# X-Fence website (staging build, round 2)

One-page site for X-Fence (Clear View fencing, George). Built by Conversion Advantage, November 2026.

- `index.html` holds the whole site (HTML, CSS and JS in one file).
- `assets/` holds the images, favicon and share image.
- The stock image sources are kept outside this repo, in the Drive folder `xfence-poc/images-temp` (see `_image-sources.txt` there for licences).

## Images used from images-temp
- fence-02 (hero), fence-03 (Residential), fence-06 (Commercial), fence-01 (Industrial)
- home-01 (the view behind the aperture viewer, cropped above its own fence)
- manufacturing-01 (manufacturing banner), manufacturing-04 (workshop)
- mesh-2 and mesh-4 are X-Fence's own product photos from the current site.
Not used: palisade, bar, slat and gate photos, green-coated mesh, laser cutting, steel coils.
Round 1 files (factory, hero-premises, mesh-1, mesh-3) are not in this repo; they remain in the Drive folder.

## Things to change before go-live
- Remove the `noindex, nofollow` robots line near the top of `index.html`.
- `og:image` points at the staging address (conversionadvantage00.github.io/xfence_staging). Change it to the live domain.
- Contact routing lives at the top of the script at the bottom of `index.html`
  (`WA_NUMBER`, `SALES_EMAIL`). WhatsApp currently points to Gavin, 083 391 0453.
- The logo is a text wordmark. Swap in the client's logo file when supplied.

## How the quote builder works
No server is needed. It opens a pre-filled WhatsApp chat or an email to
sales@xfence.co.za with the fence size and the visitor's details.
