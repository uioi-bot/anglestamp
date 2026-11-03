# AngleStamp Camera

A camera web app for your phone. It stamps each photo with the date and time, GPS coordinates, compass azimuth, tilt, roll and your notes. While you aim, the viewfinder shows a protractor, a horizon line and a compass tape.

## Put it on your phone

The camera, GPS and motion sensors only work when the app is opened from an **https://** address, so the folder has to be hosted somewhere first. Either option below is free.

**Option A: Netlify Drop (about 2 minutes)**
1. On your PC, go to https://app.netlify.com/drop and sign in (a free account keeps the site online).
2. Drag this whole `anglestamp` folder onto the page.
3. You get an address like `https://something.netlify.app`. Open it in **Chrome** on your S24 Ultra.

**Option B: GitHub Pages**
1. Create a repository and upload the files from this folder.
2. Go to Settings → Pages → Deploy from branch → `main` / root.
3. Open `https://<your-name>.github.io/<repo>/` in Chrome on the phone.

**Install it like an app:** in Chrome, tap ⋮ → **Add to Home screen** → **Install**. It then opens full-screen from its own icon and keeps working without internet.

The first time it opens, allow **Camera** and **Location**.

## Using it

- **Note box:** type the note for the next photo. Tap **Keep** to clear the note after each shot instead of keeping it. Notes you've used before show up as suggestions.
- **Project chip** (top left): sets a project or site name, printed as the first line of the stamp.
- **HOLD** freezes the angle readings. **ZERO** makes the current tilt and roll read 0° (tap again to clear it).
- Point the camera at the floor or ceiling and the horizon changes into a bubble level.
- A Bluetooth shutter remote that sends Enter or a volume key will take a photo.
- **Thumbnail** (bottom left): your photos, with Share, Save to phone, Map and Delete. Use **Export log (CSV)** to get a spreadsheet of every photo's time, coordinates, angles and notes.

## Settings (Setup)

- **Stamp:** choose which fields to print, the position (any corner or a full-width bar), text size, style, date format, 12/24-hour time, coordinate format (decimal or degrees-minutes-seconds), a compass rose, and whether the angle scales are drawn on the photo.
- **Photo:** aspect ratio (4:3, 16:9, 1:1, full), camera resolution (up to 4K), capture mode, saved size, JPEG quality, lens, and whether every photo is also saved to the phone automatically.
- **Viewfinder:** grid, self-timer, and lens field of view (lines up the horizon ladder).

## Good to know

- Photos are kept inside the app until you tap **Save** or **Share**, or until you turn on "Also save each photo to phone". Clearing Chrome's site data deletes photos you haven't saved.
- Every saved JPEG also carries the GPS position, time, azimuth and note in its EXIF data, so Google Photos and map tools can place it.
- Azimuth is magnetic north, from the phone's compass. If it drifts, move the phone in a figure-8 to recalibrate.
- A web app can't use Samsung's 50MP or 200MP modes or its night processing. Most photos are 4K-class (about 8–12 MP).
