ORBIT v6 by Malel - Skyworth 55 inch Google TV (Android 11).
1. Unzip, upload the CONTENTS to your GitHub repository (overwrite existing files).
2. Check .github/workflows/build.yml exists (copy in build-workflow-copy.txt).
3. Actions tab: wait for the green tick. Releases: download OrbitTV.apk.
4. TV: Downloader > the release link > Install. Same signing key as before, so it updates v3/v4/v5 in place.

What is new in v6
- Home is its own page: empty space on top, a Widgets row (fold it with the Widgets button), then your 9 apps at the bottom.
- Other pages (Apps, Widgets, Discover, Biglel, Theme) sit behind the arrow button next to Home.
- Choose your Home apps: hold OK on a Home app, or Arrow > Apps > Customize Home.
- Widgets: scenic places, wild animals, Marvel, DC, anime, your own photos, online search, image links, clock.
- Real photos only (Wikimedia Commons). The drawn illustrations are gone from Biglel, Theme and widgets.
- Theme > Photo backgrounds: categories, online search, image link, TV gallery.
Photos need internet. Marvel/DC/anime photos are cosplay and convention photos (official art is copyrighted).
Optional home screen: adb shell cmd package set-home-activity com.orbit.tv/.MainActivity
Undo: adb uninstall com.orbit.tv
