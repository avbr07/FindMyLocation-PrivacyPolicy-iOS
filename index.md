# Privacy Policy for Find My Location — iPhone

**Last updated:** September 2, 2026  
**Developer:** PlayMine  
**Bundle ID:** net.playmine.findmylocation  
**Platform:** iPhone (iOS)

> ### Which app this describes
>
> **This policy covers the iPhone app only.** Find My Location also exists on Android, and the two
> are separate apps that answer the same questions by asking different people. The Android app is
> covered by its own policy at
> <https://avbr07.github.io/FindMyLocation-PrivacyPolicy/>, and the services listed there are
> **not** the services this version uses.

## Overview

Find My Location ("the App") is a utility that shows your current location, address, weather, travel
speed, altitude and flight height, compass heading and steps — and keeps a short, on-device-only log
of your recent trips so you can view the routes you travelled.

The App has **no servers, no account and no sign-in.** We receive nothing from it.

## Data Collection

The App does **NOT** collect, store, or transmit any personal data to servers operated by us. We do
not require an account, sign-in, or any personal details.

🔑 **The iPhone app contains no analytics of any kind.** There is no usage counting, no tracking SDK,
no advertising SDK, and no crash-reporting service. Nothing measures how you use the App. (The
Android version counts anonymous app-open events; this version does not, and there is therefore no
setting to turn off.)

## Location Data

Your position comes from iOS Core Location — GPS, Wi-Fi and cellular positioning, handled by the
system on your device. It is used to show where you are, your address, local weather, your speed and
altitude, and to record trips you have asked the App to record.

Coordinates leave your device only to answer a request you have caused, and only to the services
listed in **The complete list of services this app contacts** below. Nothing else is ever sent, and
your coordinates are never used for advertising or profiling.

**Working out the place name and the ground elevation happens entirely on your device**, from data
shipped inside the App. Travelling with the App open sends nothing for either.

## Background Location

The App offers **Keep running in background**, which is **off until you turn it on**. When it is on,
the App keeps updating and announcing your location and recording your trip's speed and distance
while the screen is locked or the App is in the background. You start it yourself and can stop it at
any time from the Location tab.

- iOS shows its own indicator while an app is using your location in the background, so the system
  always tells you when this is active — independently of anything the App displays.
- Background location is used **only** for the features you switched on: live location, address,
  voice announcements, and on-device trip recording. It is never used for advertising or profiling,
  and never shared beyond the services listed below.
- Trip routes recorded in the background stay in the same on-device trip history described below and
  are never transmitted.
- Background location stops when you switch the feature off.

**Trip recording** is a separate switch, also off until you turn it on, reachable from Settings or
the top of the Trips tab. It saves your walks and drives to the on-device Trips tab and never
announces or geocodes anything.

## Motion & Fitness

With your permission, the App reads your iPhone's motion sensor (Core Motion) for two purposes:

- to show steps, calories and distance walked on the Speed tab, and
- to tell a walk from a drive in your trip list.

**All of it stays on your phone.** No motion data is transmitted anywhere. Refusing this permission
disables only the step counter and the walk/drive distinction; everything else works normally.

## Trips — Kept On Your iPhone

Trips are recorded and kept **only on your iPhone**, and are never uploaded.

- The App keeps your **7 most recent travel days**; older days are removed automatically.
- You may bookmark up to **30 trips to keep**. Those are exempt from the automatic pruning and stay
  until you delete them.
- Nothing about a trip — the route, the place names, the times, the distance — is transmitted to us
  or to anyone else.

## Your Own Copies — Backup, Restore and Sharing

This is the one part of the App where your data can leave the protection of your phone, and only you
can decide that. **The App still never uploads anything, and we still have no servers and receive
nothing** — but a copy you create is yours to look after, and what happens to it afterwards is
outside the App's control.

- **Back up (Settings).** Writes your trips, their routes and your step history to a single file, at
  a location you choose through the iOS Files interface — on your iPhone, in iCloud Drive, or in
  another provider you have connected. If you choose a cloud location, that file is then held by
  that provider under **their** privacy policy, not this one.
- **Restore (Settings).** Reads a file you select and adds its trips to this phone.
- **Share or save a trip.** Hands one journey to whichever destination you pick from the iOS share
  sheet. Whoever receives it can see everywhere that journey went.
- **Nothing leaves your phone until you choose a destination.** No backup or file is created or sent
  in the background, on a schedule, or without you asking for it.
- **A copy you have made is not covered by the App's own deletion.** Deleting the App removes
  everything inside it, but it cannot reach a file you saved elsewhere or a trip you already sent to
  somebody. **Treat a backup file as you would a diary of where you have been.**

## Voice Announcements

The App can read your current place name aloud using your iPhone's built-in speech synthesiser. **No
audio, and no location text, is sent off the device for this feature.**

## The Complete List of Services This App Contacts

| Service | Purpose | Data Sent | Privacy Policy |
|---------|---------|-----------|---------------|
| Apple — Core Location | Your position (GPS / Wi-Fi / cellular) | Handled by iOS on your device | https://www.apple.com/legal/privacy/ |
| Apple — Maps, place search and geocoding | The map itself; nearby fuel, food and medical results; turning coordinates into a street address, and text you type into the Map search box into a point on the map | Lat/Lon coordinates, the search radius, and the text you type. Apple states that this is not tied to your Apple Account | https://www.apple.com/legal/privacy/ |
| **On-device attractions list (OpenStreetMap, ODbL)** | Attractions and landmarks | **Nothing — the data ships inside the app and never leaves your device** | https://osmfoundation.org/wiki/Privacy_Policy |
| **On-device place list (GeoNames, CC BY 4.0)** | Town/city/region/country name with no connection | **Nothing — ships inside the app** | https://www.geonames.org/ |
| **On-device elevation grid** | Ground elevation for "flight height" | **Nothing — ships inside the app** | — |
| OpenWeatherMap | Weather where you are | Lat/Lon coordinates, IP | https://openweather.co.uk/privacy-policy |
| Open-Meteo | Weather (fallback only) | Lat/Lon coordinates, IP | https://open-meteo.com/en/terms |
| Apple — App Store ratings prompt | The occasional "rate this app" prompt | None (system-level) | https://www.apple.com/legal/privacy/ |

**That is the entire list. There is no other outbound connection in the iPhone app.**

In particular, this version **never contacts the OpenStreetMap tile servers, the Overpass API,
Nominatim or the Wikidata Query Service.** Those services appear in the Android app's policy and are
not part of this one.

## What Works With No Connection

Your position, speed, altitude, compass and step count all work with no data connection, because
they come from your iPhone's own sensors. In addition, these ship **inside the App** and never
involve a network request:

- over half a million notable places, for attractions and landmarks;
- the world's towns and cities, for naming where you are with no connection; and
- the elevation grid behind "flight height".

Looking up nearby places through Apple's search, and fetching weather, need a connection.

## Advertising

The current version of the App does **not** display advertisements, and contains no advertising SDK.
If ads are introduced in a future version, this privacy policy will be updated before that version
ships.

## Permissions

| Permission | Purpose | Optional? |
|-----------|---------|-----------|
| Location — While Using the App | Your location, address, weather, speed, altitude, and the on-device trip log | Required for the App's core purpose |
| Location — Always | Only if you turn on **Keep running in background**, so announcements and trip recording continue while the screen is locked | **Yes** — off until you switch it on |
| Motion & Fitness | Steps, calories and distance walked; telling a walk from a drive | **Yes** — denying it disables only those features |

Each is explained on screen at the moment iOS asks, and you can change any of them at any time in
the iOS **Settings** app under **Privacy & Security**, or under **Find My Location** in the app list.

## Data Storage

Everything the App writes to disk is in the App's **private, sandboxed container**, which iOS
prevents other apps from reading, and all of it is removed when you delete the App:

- the **on-device trip history** described above;
- your **step history**; and
- **app preferences** — the voice-announcement setting, voice, speed and volume, the announcement
  interval, the keep-screen-awake setting, the preferred speed unit (mph/km/h), the preferred
  temperature unit (°F/°C), and counters used to decide when to show the ratings prompt.

If you choose to enter your body weight — used only to estimate calories from your steps — it is
stored on-device only and never leaves your phone.

**Files you create yourself are the exception**, and are not in the App's private container. A
backup file, or a trip you saved or shared, sits wherever you chose to put it. The App cannot read,
manage or delete it afterwards, and deleting the App does not remove it.

**No personal information is collected by us.**

## Data Retention

We operate no servers and retain **no user data of any kind** on our side. All data the App uses
lives only on your device, with these retention periods:

| Data | Where it is kept | How long |
|------|------------------|----------|
| Trip history (routes, place names, times) | App's private on-device container | Your **7 most recent travel days** |
| Trips you chose to keep (bookmarked, max 30) | App's private on-device container | **Until you delete them** — exempt from the automatic pruning, never transmitted |
| Step history | App's private on-device container | Until you delete the App |
| Backups, and trips you saved or shared | **Wherever you chose to put them** — not the App's container | **Until you delete them.** The App cannot reach them, and deleting the App does not remove them |
| Current location, address, weather, speed, altitude, compass | Device memory only | Discarded when tracking stops or the App closes |
| App preferences (units, voice settings, optional body weight) | App's private on-device container | Until you delete them or delete the App |

The third-party services listed above receive coordinates transiently to answer each request; we do
not control their retention, which is governed by their own privacy policies linked in the table
above. Place names and ground elevation are worked out entirely on your device and involve no third
party at all.

## Data Deletion

Because we never collect or store your data on any server, **there is no data for us to delete** —
everything is on your device and under your control.

- **Delete everything the App holds:** delete the App from your iPhone. This permanently removes the
  trip history, the step history, all preferences, and any stored weight.
- **⚠️ Copies you made yourself are not included, and you must delete them yourself.** A backup file,
  a saved trip, or one you shared is wherever you put it — on your iPhone, in iCloud Drive, or on
  somebody else's device. The App has no way to reach it, and deleting the App will not remove it.
  Remember that anything already sent to somebody else cannot be taken back.
- **Trip history** also prunes itself automatically: only your 7 most recent travel days are kept,
  apart from trips you bookmarked to keep. You can un-bookmark one at any time to hand it back to the
  automatic pruning.

If you have any questions or requests regarding your data, contact us at
**playmine.support@gmail.com** and we will respond promptly.

## Data Sharing

We do not sell, trade, or share your data with any third party beyond the services described above,
each of which receives only what it needs to answer the request. **The App itself never shares a
trip with anyone.** The one way a journey reaches another person or service is if **you** send it —
through the backup, save or share actions described above — and then only to the destination you
pick, at the moment you pick it.

## Data Security & Handling

- Location is processed **on your device**. Everything the App writes to disk is stored in its
  private, sandboxed container. A backup or shared trip that **you** create is deliberately outside
  that sandbox, because the point of it is to survive the App being removed; from that moment its
  safety is in your hands.
- All network communications use **HTTPS/TLS encryption** and carry only coordinates and the text
  you type into search — never your name, contacts, identifiers, or anything else, because the App
  never has such information.
- No personal data is ever transmitted to servers operated by us; we have no servers and no user
  database.

## Children's Privacy

The App does not knowingly collect data from children under 13. The App does not require account
creation or personal information.

## Changes to This Policy

We may update this privacy policy from time to time. Changes will be reflected in the "Last updated"
date above. Continued use of the App constitutes acceptance of the updated policy.

## Contact

If you have questions about this privacy policy, contact us at:  
📧 playmine.support@gmail.com

## Consent

By using Find My Location on iPhone, you consent to this privacy policy.
