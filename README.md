<div align="center">
<img width="150" height="150" src="Pocket Poster/Assets.xcassets/AppIcon.appiconset/badposter tinted.png" alt="Bad Poster icon">
</div> <div align="center">
  <h1><b>Bad Poster</b></h1>
  <p><i>Custom PosterBoard wallpapers for iOS 17+ · bad_query support for iOS 26–27.0b4</i></p>
  <p>
    Forked from <a href="https://github.com/leminlimez/Pocket-Poster"><b>Pocket Poster</b></a>
    · iOS 27 port by <a href="https://github.com/Mak5er"><b>Mak5er</b></a>
    · Redesigned and maintained by <a href="https://github.com/nxtcoreee3"><b>nxtcoreee3</b></a>
  </p>
</div>

## What’s New in Bad Poster

Bad Poster keeps the original Pocket Poster workflow and adds a Bad Poster identity, persistent wallpaper Favorites, and a multi-provider Explore experience.

- **Persistent Favorites** — Save imported `.tendies` files and provider wallpapers locally on the device. Favorites survive relaunches and can be queued later from the Favorites tab.

- **Provider selection** — Choose **Cowabunga**, **CAPlayground**, or **Both** in Explore.

- **CAPlayground support** — Browse CAPlayground’s public catalog, view previews and creator information, and download direct `.tendies` files.

- **Instant favorite state** — Saved wallpapers show a filled star; unsaved wallpapers show an outlined star. Failed remote downloads roll back the temporary state.

- **Bad Poster UI** — Includes Bad Poster branding, a red onboarding accent, liquid-glass-inspired controls, provider filtering, search, and refreshed wallpaper cards.

- **Original workflow retained** — Import wallpapers and videos, apply collections, detect PosterBoard on-device where `bad_query` works, reset collections, and respring.

## Download

Latest IPA: [**Bad Poster Releases**](https://github.com/nxtcoreee3/Bad-Poster/releases/latest)

CI can build an unsigned IPA on pushes to `main` and publish a GitHub Release when a version tag is pushed, depending on the repository Actions configuration.

```bash
# cut a release from your machine
git tag v3.3.0 && git push origin v3.3.0
```

## Getting Started

### iOS 26 / 27.0b4 (`bad_query`)

On versions where [badquerygithub] works, **no computer is required** after sideloading:

1. Install the IPA with TrollStore, SideStore, or another compatible method.

1. Open **Settings → Detect On-Device**, or select wallpapers and use **Apply** to trigger automatic hash detection.

1. Import `.tendies` files, download wallpapers from Explore, or add saved Favorites to the queue.

1. Select wallpapers or videos and choose **Apply**. Bad Poster applies the collection and performs a full respring where supported.

**Reset Collections** removes custom PosterBoard descriptors through the supported `bad_query` path and then resprings the device.

### Older iOS and legacy environments

You may need a computer to obtain the PosterBoard App Hash or UUID. Download [nuggetgithub], connect your phone, and follow the helper and detection instructions in Bad Poster Settings. Compatibility depends on the iOS version and jailbreak environment.

## Wallpaper Sources

- [cowabungawallpaperspage]

- [caplaygroundwallpaperspage]

- [caplaygroundmanifest]


In Explore, select **Cowabunga**, **CAPlayground**, or **Both**. Search by wallpaper name, creator, or description. Cowabunga’s wallpaper categories and filters remain available, and both providers use the same download and Favorites workflow.

## Favorites

Favorites are stored on-device in the app’s Documents directory under a dedicated Favorites folder. Bad Poster keeps local copies of favorited `.tendies` files and a metadata index so saved wallpapers remain available after relaunch.

Imported wallpapers can be starred from the selected `.tendies` list on Home. Cowabunga and CAPlayground wallpapers can be starred directly from Explore. Open the **Favorites** tab to queue a saved wallpaper for applying or remove it with the standard list actions. Favorites are device-local and are not synchronized to GitHub or a remote account.

## Videos and Settings

The **Videos** tab imports videos from the Photos library for use in the PosterBoard workflow. The **Settings** screen provides hash entry, on-device detection, reset actions, CarPlay hash configuration where supported, social links, and the full in-app Credits list.

## Building from Source

```bash
git clone https://github.com/nxtcoreee3/Bad-Poster.git
cd Bad-Poster
open "Pocket Poster.xcodeproj"
```

Select the **Pocket Poster** scheme in Xcode and build for a connected device or simulator. The project’s usable iOS versions depend on the target device, jailbreak environment, PosterBoard behavior, and `bad_query` support.

## Credits

- [nxtcoreee3] — Bad Poster fork, UI and liquid-glass redesign, branding, onboarding, Favorites workflow, provider integration, documentation, and ongoing maintenance

- [enkei64] — CAPlayground development and wallpaper catalog

- [mak5er] — `bad_query` port, iOS 27 build work, full respring, and on-device detection

- [lemin] — original Pocket Poster and main PosterBoard tooling

- [serstars] — website design

- [nathan] and [duykhanhtran] — `.Trash` exploit work

- [badquery] — `bad_query` for iOS 26/27 sandbox access

- [dootskyre] — fallback shortcut creation

- **Community translators** — translations coordinated through [poeditor]

- [posterrestore] — PosterBoard assistance

## Project Status

Bad Poster is a community fork under active development. Provider catalogs, remote download endpoints, jailbreak capabilities, and PosterBoard behavior can change independently of the app. Always review a wallpaper’s source and compatibility before applying it to a device.

[cowabungawallpaperspage]: https://cowabun.ga/wallpapers "https://cowabun.ga/wallpapers"

[caplaygroundwallpaperspage]: https://caplayground.vercel.app/wallpapers "https://caplayground.vercel.app/wallpapers"

[caplaygroundmanifest]: https://raw.githubusercontent.com/CAPlayground/wallpapers/refs/heads/main/wallpapers.json "https://raw.githubusercontent.com/CAPlayground/wallpapers/refs/heads/main/wallpapers.json"

[nugget]: https://github.com/leminlimez/Nugget "https://github.com/leminlimez/Nugget"

[lemin]: https://github.com/leminlimez "https://github.com/leminlimez"

[mak5er]: https://github.com/Mak5er "https://github.com/Mak5er"

[nxtcoreee3]: https://github.com/nxtcoreee3 "https://github.com/nxtcoreee3"

[enkei64]: https://github.com/enkei64 "https://github.com/enkei64"

[serstars]: https://github.com/SerStars "https://github.com/SerStars"

[cowabunga]: https://discord.gg/cowabunga "https://discord.gg/cowabunga"

[posterrestore]: https://discord.gg/gWtzTVhMvh "https://discord.gg/gWtzTVhMvh"

[poeditor]: https://poeditor.com/join/project/MPZOsunwVj "https://poeditor.com/join/project/MPZOsunwVj"

[dootskyre]: https://bsky.app/profile/did:plc:xykfeb7ieeo335g3aly6vev4 "https://bsky.app/profile/did:plc:xykfeb7ieeo335g3aly6vev4"

[nathan]: https://github.com/verygenericname "https://github.com/verygenericname"

[duykhanhtran]: https://github.com/khanhduytran0 "https://github.com/khanhduytran0"

[badquery]: https://github.com/forcequitOS/bad_query "https://github.com/forcequitOS/bad_query"
