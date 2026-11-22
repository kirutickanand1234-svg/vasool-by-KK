VASOOL COLLECTION - upload ALL of these files to your GitHub repo (replace old ones):
  index.html, manifest.json, icon-v3-*.png, apple-touch-icon-v3.png
You can delete the older icon-192.png, icon-512.png, icon-maskable-*.png, apple-touch-icon.png.

Check after GitHub Pages updates (wait ~2 minutes):
  1) Open  <your-site>/manifest.json   -> it must say "name": "Vasool Collection"
  2) Open  <your-site>/icon-v3-maskable-512.png  -> you must see the green KK square

Then UNINSTALL the old Vasool app from the phone and install again.
If you build the APK with PWABuilder: paste your site link, then in Android options set
  Icon URL            = <your-site>/icon-v3-512.png
  Maskable icon URL   = <your-site>/icon-v3-maskable-512.png
  App name / Short name = Vasool Collection
and install the newly downloaded APK after uninstalling the old one.
