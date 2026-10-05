# Weather or Not: background photos

The photo pack for the Weather or Not Android app: the photo behind each place's page. `photos.json` lists each area: a centre, a radius in
miles, and its day photo (and, optionally, a night photo). A place uses the photo of the nearest
area whose circle it's inside, by the place's own position (GPS or saved place). Places outside
every circle keep the plain sky background.

To add or change a photo: put `day.jpg` (and `night.jpg`) in a folder for the area, add the area to
`photos.json`, and raise `version`. Portrait photos about 768 × 1376 work best, scenery only.

The phones check this repository once a day. When `version` here is higher than the pack they
have, they download every photo, then the list, and switch over; no new app build is needed. A copy
is built into the app (app/src/main/assets/photos), so keep the two in step when releasing.

This repository is public: scenery only, no people, no home addresses.

| Area | Centre | Radius | Day | Night |
|---|---|---|---|---|
| St. Louis, MO | Gateway Arch (38.6247, -90.1848) | 25 mi | ✓ | ✓ |
| Chicago, IL | Millennium Park (41.8826, -87.6226) | 30 mi | ✓ | ✓ |
| Minneapolis–St. Paul, MN (to Hudson, WI) | Spoonbridge and Cherry (44.9697, -93.2890) | 30 mi | ✓ | ✓ |
| Brothertown–Pipe, WI | Brothertown (43.968, -88.309), Lake Winnebago | 20 mi | ✓ | ✓ |
| Fort Myers, FL | Edison and Ford Winter Estates (26.6343, -81.8798) | 25 mi | ✓ | ✓ |
