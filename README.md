# Starry Night for SteamEdge

A theme-only patch for [SteamEdge](https://github.com/Miabeyefendi/SteamEdge).
It adds a Starry Night option in Settings, a black-to-navy sky, small twinkling
stars, and shooting stars. The sky also appears on the sign-in screen.

The patch was made against upstream commit `7724dc8` (SteamEdge 1.3.3). It
changes six theme-related files. There are no account settings or app binaries
in this repository.

## Apply to the source

1. Clone [SteamEdge](https://github.com/Miabeyefendi/SteamEdge) and check out
   commit `7724dc8`.
2. Download [SteamEdge-StarryNight.patch](SteamEdge-StarryNight.patch) into the
   cloned repository.
3. Run `git apply --check SteamEdge-StarryNight.patch`, then
   `git apply SteamEdge-StarryNight.patch`.
4. Run SteamEdge from source using its own instructions. In Settings, choose
   **Starry Night** and save.

The theme honors the system's reduced-motion preference. The original
[Spicetify StarryNight](https://github.com/spicetify/spicetify-themes/tree/master/StarryNight)
theme is credited to Brandon Chen and Julissa Laignelet. This SteamEdge port is
by [BraxF](https://github.com/braxffa). See
[the theme notices](STARRY_NIGHT_NOTICES.md) for the licenses and shooting-star
credit. SteamEdge itself is by [Miabeyefendi](https://github.com/Miabeyefendi).
