<div align="center">
   <img width="150" height="150" src="Pocket Poster/Assets.xcassets/AppIcon.appiconset/badpostertinted.png">
</div>

<div align="center">
  <h1><b>Pocket Poster</b></h1>
  <p><i>Custom PosterBoard Wallpapers for iOS 17+ · bad_query for iOS 26–27.0b4</i></p>
  <p>Maintained / iOS 27 port by <a href="https://github.com/Mak5er"><b>Mak5er</b></a></p>
</div>

## Download

Latest IPA: [**Releases**](https://github.com/Mak5er/Pocket-Poster/releases/latest)

CI builds an unsigned IPA on every push to `main` and publishes a GitHub Release when you push a tag like `v3.2.2` (or run **Release IPA** from Actions).

```bash
# cut a release from your machine
git tag v3.2.2 && git push origin v3.2.2
```

## Getting Started

### iOS 26 / 27.0b4 (bad_query)
On versions where [bad_query][badQueryGitHub] works, **no computer is required**:
1. Install the IPA (sideload with TrollStore / SideStore / etc.).
2. Settings → **Detect On-Device** (or just hit Apply — hash auto-detects).
3. Select tendies / video → **Apply** → device does a **full respring** (Frontboard + Backboard).

**Reset Collections** wipes PosterBoard descriptors via bad_query, then full resprings the same way.

### Older iOS (legacy .Trash exploit)
You will need a computer to get the App Hash/UUID.

Download [Nugget][NuggetGitHub] on your computer and plug in your phone.
<br>Then, navigate to the `Settings` page and click the `Pocket Poster Helper` button. 
<br>Inside Pocket Poster, click the `Detect` button inside of settings.

Community-made wallpapers can be found on the [official Cowabun.ga site][CowabungaWallpapersPage].
<br>Join the [Cowabunga Discord Server][CowabungaDiscord] for additional help.

## Credits
- **[Mak5er][Mak5erGitHub]** — bad_query integration, iOS 27 port, full respring, on-device detect
- [LeminLimez][LeminGitHub] — original Pocket Poster
- Translations crowdsourced using [POEditor][POEditorJoin]
- [PosterRestore][PosterRestoreDiscord] for their help with PosterBoard
- [dootskyre][dootskyreX] for the fallback shortcut
- [Nathan][NathanGitHub] and [DuyKhanhTran][DuyKhanhTranGitHub] for the .Trash exploit
- [forcequitOS][badQueryGitHub] for bad_query (iOS 26/27 sandbox escape)
- [SerStars][SerStarsX] for creating the website

[CowabungaWallpapersPage]: https://cowabun.ga/wallpapers
[NuggetGitHub]: https://github.com/leminlimez/Nugget
[LeminGitHub]: https://github.com/leminlimez
[Mak5erGitHub]: https://github.com/Mak5er
[CowabungaDiscord]: https://discord.gg/cowabunga
[PosterRestoreDiscord]: https://discord.gg/gWtzTVhMvh

[POEditorJoin]: https://poeditor.com/join/project/MPZOsunwVj
[dootskyreX]: https://x.com/dootskyre
[NathanGitHub]: https://github.com/verygenericname
[DuyKhanhTranGitHub]: https://github.com/khanhduytran0
[SerStarsX]: https://x.com/SerStars
[badQueryGitHub]: https://github.com/forcequitOS/bad_query
