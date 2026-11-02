# OpenMaps

### Offline maps. On your wrist.

OpenMaps brings simplified OpenStreetMap maps and GPX routes to compatible Garmin
Instinct watches, with Europe and North America in one app. Choose a location;
the service selects the regional archive automatically.

**Release status — 3 November 2026:** the OpenMaps 1.0 production update is
prepared. Server rollout and the Connect IQ release are pending. These unified
instructions apply after both updates are installed. The current store app may
still be named EuropeMaps. This documentation update does not deploy the server
or upload a watch release.

[Maps & routes](https://openmaps.duckdns.org/routes) ·
[Premium & restoration](https://openmaps.duckdns.org/premium) ·
[Connect IQ listing](https://apps.garmin.com/apps/f5cd5919-84f9-41b3-b5c7-276a154039bc)

## Features

- Simplified streets, paths, waterways and selected OpenStreetMap names.
- Free 2 × 2, 4 × 4 and 8 × 8 km downloads; one saved route with its map corridor.
- North up or Direction up, GPS following, zoom, pan and recenter.
- GPX import through the website and matching offline corridor downloads.
- Walking, hiking and cycling recording, saved and synced through Garmin Connect.
- Up to five saved map areas or route-corridor pairs within available storage;
  one is loaded at a time.

OpenMaps Premium adds 16 × 16 and 24 × 24 km maps and multiple saved routes.
The new release's price is **EUR 5.49 once**, with no subscription. One license
covers all supported regions on one active watch installation. Current coverage
is Europe and North America; the app does not yet cover every country worldwide.
Normal download quotas, archive coverage and technical storage limits apply.

Existing eligible EuropeMaps Premium purchases carry over, including purchases
at the former price. The shop remains the existing
[BMC Premium item](https://buymeacoffee.com/asparaguss/e/592998). Its checkout price
must be updated before the new offer launches; always check the final payable
amount before buying. Donations are separate from Premium.

## Update and start

OpenMaps updates the existing EuropeMaps production app identity. Update through
Connect IQ without uninstalling to retain saved content and installation data.
Separately installed beta apps have their own storage and credentials.

1. Open OpenMaps on the watch and Garmin Connect on the paired phone.
2. Hold **MENU → Download maps → Choose on phone**. Keep the app open.
3. Accept the browser link or visit the maps-and-routes page and enter the watch
   code. No Garmin login or separate OpenMaps password is needed on our website.
4. Select a search result or tap the map, choose a size, preview and send.
5. Return to Garmin Connect if prompted and keep the phone connected until done.

No map is bundled. Downloads require a paired phone, internet and an available
server. Saved maps work offline. Around me requires an outdoor GPS fix. Maps
are simplified; some detail is omitted. No turn-by-turn instructions or automatic
rerouting are provided.

[Setup and controls](SETUP.md) · [Troubleshooting](SUPPORT.md) ·
[Privacy policy](https://asparaguss.github.io/openmaps/)

## Supported watches

Instinct 3 Solar 45/50 mm and Instinct E 40/45 mm. Check the Connect IQ
compatible-device list for your exact watch. No additional models are announced
by this update.

## Legacy apps and services

Existing EuropeMaps clients retain their European API paths. OpenMaps 1.0 uses
one API, one request worker and the existing primary licensing/accounting state
for both regions. The production migration retires the unused separate NAMaps
API and worker. Its old /na endpoints return 410 after migration. Move from the
separate NAMaps beta to OpenMaps; its storage cannot be automatically transferred
between different Garmin application identities. Existing eligible Premium
purchases can be restored using purchase-email verification. Old NA state and
archives are retained on disk; usage is not retroactively merged.

## Support and repository

[Report an issue](https://github.com/Asparaguss/openmaps/issues/new/choose) or email
[asparaguss@proton.me](mailto:asparaguss@proton.me). Include app/build, watch model,
phone platform and exact error. Never post pairing codes, secrets or private tracks.

This public repository contains documentation, support and privacy information.
Watch/server source, signing keys, credentials, runtime databases and full map
archives remain private. Install app updates through Connect IQ.

Map data © [OpenStreetMap contributors](https://www.openstreetmap.org/copyright),
ODbL 1.0. Place names include [GeoNames](https://www.geonames.org/), CC BY 4.0.
OpenMaps by Asparagus is independent of Garmin; Garmin and Connect IQ are Garmin
trademarks.
