# OpenMaps setup and controls

[Install/update through Connect IQ](https://apps.garmin.com/apps/f5cd5919-84f9-41b3-b5c7-276a154039bc) · [README](README.md) · [Troubleshooting](SUPPORT.md)

## Choose your app and region

The common controls below apply to EuropeMaps and NorthAmericaMaps. Where the instructions say EuropeMaps, use the app matching your region.

| App | Website | Area sizes |
| --- | --- | --- |
| EuropeMaps | https://openmaps.duckdns.org/routes | Free 2/4/8 km; Premium 16/24 km |
| NorthAmericaMaps (NAMaps) | https://openmaps.duckdns.org/na/routes | Free 2/4/8 km; Premium is not available |

Use the link and code supplied by the app currently open on the watch. Separate beta apps have their own installation credentials. A EuropeMaps Premium purchase does not activate NorthAmericaMaps.

NorthAmericaMaps GPX corridors are limited to 64 tiles within an 8 × 8 km bounding box; long or complex routes may need shortening. Up to five areas/corridor pairs share storage. Route availability follows the current app's free/Premium limits.

## First map: choose on your phone

1. Pair a compatible Instinct with Garmin Connect on iPhone or Android and install EuropeMaps.
2. Leave **Map server → Default** in Connect IQ settings. Leave custom/private URLs blank for normal use.
3. Open EuropeMaps on the watch and Garmin Connect on the phone. Garmin Connect and the Connect IQ Store are different apps.
4. On the watch, hold MENU and choose **Download maps → Choose on phone**. A temporary code appears.
5. Accept the browser link on your phone. If necessary, press GPS on the code screen after opening Garmin Connect. Or visit [your regional Maps & Routes page](#choose-your-app-and-region) and enter the code manually. Codes expire after ten minutes and work for one transfer.
6. Search for a city or street and **tap the matching result beneath the search field**. Alternatively, tap the map anywhere to set the centre without searching first.
7. Choose an available side length: 2, 4 or 8 km free; 16 or 24 km requires EuropeMaps Premium. The outline previews the selected coverage. Start small: larger downloads take longer and share the app's limited storage.
8. Choose Preview download area, review the confirmed coverage and start the transfer. Choose Load interactive map to see the map and boundary; loading it shares connection and tile-region information with OpenStreetMap. Checking coverage alone does not start the watch download.
9. Keep EuropeMaps open and return to Garmin Connect. Follow progress on the watch. If phone standby interrupts a transfer, keep Connect in the foreground until it finishes.

A fresh installation has no bundled map. Browsing a saved map works offline; downloads require the connected phone's internet access.

## Alternatives

**Around me:** choose MENU → Download maps → Around me / GPS outdoors and wait for a usable fix. The selected area is centred near that position; the phone still needs internet access.

**Location search:** in the Connect IQ settings, enter a city or street under Location to Download, choose the area size, save and sync. Open EuropeMaps to continue. This shortcut uses a search-result centre; use the website to choose a precise centre. Save the default server selection unless you intentionally use a different server.

## Import a GPX route

1. Keep Garmin Connect open on the phone. On the watch, choose **MENU → Route Navigation → Import route**.
2. Open the supplied website link or visit [your regional Maps & Routes page](#choose-your-app-and-region) and enter the watch's code.
3. Choose a GPX file, enter a route name, review its corridor and check coverage. Start the transfer when ready.
4. Return to Garmin Connect and keep the watch app open. The watch receives the route and downloads the required corridor tiles automatically.
5. Under **Route Navigation**, select the saved route and choose **Use route** to load its matching corridor.

For a course in Garmin Connect Web: open **Training & Planning → Courses**, choose the course, then use its three-dot menu to export/download GPX. Select that file on the EuropeMaps website. EuropeMaps does not ask for your Garmin password or connect to your Garmin account. The route length is not limited to a square's side length, but tile, point, coverage and storage limits still apply.

Multiple saved routes require EuropeMaps Premium. NorthAmericaMaps currently allows its free route features within the shared five-area storage allowance. A linked route's **Delete route + map** action removes both the route and its corridor. Other saved areas remain. You can later import the same route again.

## Record an activity

Choose **MENU → Activity → Start walking / Start hiking / Start cycling**. You can request a start before GPS reception; actual recording waits for a usable fix. The app shows GPS-search status while waiting.

Use **MENU → Activity → Pause activity**, **Resume activity** or **Finish activity**. When finished, choose to save or discard. Saved activities use Garmin's native activity recording and synchronize through Garmin Connect in the normal way. EuropeMaps does not upload the recorded activity track to its map server.

## Map controls

| Button or option | Action |
|---|---|
| GPS | Cycle zoom, vertical pan and horizontal pan |
| UP / DOWN | Zoom or pan in the selected mode |
| BACK | Leave pan mode; from the map, exit or finish an active recording |
| Hold MENU | Open options |
| Recenter | Resume following a valid GPS position |
| Show map centre | Browse the centre of the active downloaded area |
| Orientation | North up or Direction up |
| Saved maps | Select, inspect or delete a saved area |
| Route Navigation | Import, select or delete a route and its corridor |
| Advanced | Backlight, names, map information and map key |

Direction up uses available heading information and places your position below centre. A reliable heading can require reception or movement. Use North up if direction is uncertain. Use the watch's own Button help screen for model-specific details.

## Storage and updates

Saved maps and route corridors share app storage; one is active at a time. Up to five entries fit only if their combined size remains within the storage allowance. Delete entries you no longer need before adding large areas.

Update through Connect IQ. Avoid uninstalling if you want to preserve maps, routes, settings and installation credentials. Current compatibility and availability are shown on the store listing; private beta features may differ.

[Privacy policy](https://asparaguss.github.io/europemaps/)
