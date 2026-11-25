# TeleTransit image assets

Background photography used across the app's hero/marketing screens (Splash,
Onboarding/Auth/Role, Home, Discover). All sourced from Unsplash under the
[Unsplash License](https://unsplash.com/license) (free to use, no attribution
required) — credited below as a courtesy.

| File | Unsplash photo | Photo page |
|---|---|---|
| `bg_splash.jpg` | Safari vehicle at sunset in savanna grassland | https://unsplash.com/photos/1516426122078-c23e76319801 |
| `bg_onboarding.jpg` | Truck on a mountain canyon road | https://unsplash.com/photos/1519003722824-194d4455a60c |
| `bg_home_hero.jpg` | Truck on an open rural highway | https://unsplash.com/photos/1601584115197-04ecc0da31d7 |
| `bg_discover.jpg` | Aerial shipping-container port | https://unsplash.com/photos/1494412574643-ff11b0a5c1c3 |

Every photo is rendered behind an `AppBackground` navy gradient scrim (see
`lib/core/widgets/app_background.dart`) so foreground text and glass cards
stay legible regardless of the photo's own contrast. All other screens use a
theme-aware ambient gradient (no photo) via the same widget.
