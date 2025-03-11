# crimera/piko

***Release Version: [v1.50.0](https://github.com/crimera/piko/releases/tag/v1.50.0)***  
***Release Date: February 08, 2025, 23:56:50 UTC***  
<details>
<summary><b><i>Changelog:</i></b></summary>

## [1.50.0](https://github.com/crimera/piko/compare/v1.49.1...v1.50.0) (2025-02-08)

### Features

* **Translations:** Update `Japanese` ([039aac3](https://github.com/crimera/piko/commit/039aac304215858769c794684f837719edad9790))
</details>

# inotia00/revanced-patches

***Release Version: [v5.4.2](https://github.com/inotia00/revanced-patches/releases/tag/v5.4.2)***  
***Release Date: March 07, 2025, 00:52:34 UTC***  
<details>
<summary><b><i>Changelog:</i></b></summary>

YouTube
==
- feat(YouTube - Settings): When the search bar in the RVX settings is activated, clicking the back button closes the search bar instead of leaving the RVX settings https://github.com/inotia00/ReVanced_Extended/issues/2723
- feat(YouTube - SponsorBlock): After the skip button is automatically hidden, makes the visibility of the skip button match the player control's https://github.com/inotia00/revanced-patches/pull/142
- fix(YouTube - Player components): `Disable player popup panels` doesn't work sometimes https://github.com/inotia00/ReVanced_Extended/issues/2814
- fix(YouTube - Return YouTube Dislike): Use correct number formatting if using a different RVX language
- fix(YouTube - Spoof streaming data): Change Default client to `Android TV` (Match with ReVanced)
- fix(YouTube - Spoof streaming data): Skip response encryption in OnesiePlayerRequest https://github.com/ReVanced/revanced-patches/pull/4521
- fix(YouTube - Spoof streaming data): Update Android VR InnerTube client (Needs testing)


YouTube Music
==
- chore(YouTube Music): Clarify strings
- feat(YouTube Music): Add `Disable QUIC protocol` patch https://github.com/inotia00/ReVanced_Extended/issues/2763
- fix(YouTube Music - Custom header): Patch error occurs in a specific environment
- fix(YouTube Music - Disable Cairo splash animation): 8.05.51 is not included in the support version https://github.com/inotia00/ReVanced_Extended/issues/2792
- fix(YouTube Music - Disable music video in album): Piped API not available https://github.com/inotia00/ReVanced_Extended/issues/2793
- fix(YouTube Music - Hide ads): `Hide premium promotion popups` setting hides the playlist dialog https://github.com/inotia00/ReVanced_Extended/issues/2798
- fix(YouTube Music - Hide layout components): `Hide sound search button` setting is not added to 8.05.51+


Shared
==
- build: Bump Gradle
- chore: Fix spelling of 'seekbar' https://github.com/inotia00/revanced-patches/pull/143
- fix(Hide ads): Change the default value of `Hide fullscreen ads` to false and add limitations to the description (Closes https://github.com/inotia00/ReVanced_Extended/issues/2812)


Announcement
==
- YouTube Music's support version has been upgraded to **7.25.53 / 8.05.51**, but please read the following issue and upgrade only if necessary: [About 7.25.53](https://github.com/inotia00/ReVanced_Extended/issues/2554), [About 8.05.51](https://github.com/inotia00/ReVanced_Extended/issues/2769).
- Compatible ReVanced Manager: [RVX Manager v1.23.5 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.23.5).


Contribute to translation
==
- [YouTube](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revancedmusicextended)
</details>

# ReVanced/revanced-patches

***Release Version: [v5.14.0](https://github.com/ReVanced/revanced-patches/releases/tag/v5.14.0)***  
***Release Date: March 09, 2025, 12:22:24 UTC***  
<details>
<summary><b><i>Changelog:</i></b></summary>

# [5.14.0](https://github.com/ReVanced/revanced-patches/compare/v5.13.0...v5.14.0) (2025-03-09)


### Bug Fixes

* **Boost for reddit - Client spoof:** Use a different user agent to combat Reddit's API issues ([5d3c817](https://github.com/ReVanced/revanced-patches/commit/5d3c8175b34a3f6ae2732b25db0851773a8c000d))
* **YouTube - Change form factor:** Restore Automotive form factor watch history menu, channel pages, and community posts ([#4541](https://github.com/ReVanced/revanced-patches/issues/4541)) ([aa5c001](https://github.com/ReVanced/revanced-patches/commit/aa5c001968446e5270c756256724e917009612cd))
* **YouTube - Hide ads:** Hide new type of buttoned ad ([#4528](https://github.com/ReVanced/revanced-patches/issues/4528)) ([4387a7b](https://github.com/ReVanced/revanced-patches/commit/4387a7b131f49729e902e008bb4cec073635c040))
* **YouTube - Hide layout components:** Do not hide Movie/Courses start page content if 'Hide horizontal shelves' is enabled ([62a6164](https://github.com/ReVanced/revanced-patches/commit/62a6164b88b64200b517a5ba6b800d8214dbbad8))
* **YouTube - Theme:** Resolve dark mode startup crash with Android 9.0 ([741c2d5](https://github.com/ReVanced/revanced-patches/commit/741c2d59406f5d602554bb3a3c0b8982f42848b4))
* **YouTube:** Change language settings menu to use native language names ([#4568](https://github.com/ReVanced/revanced-patches/issues/4568)) ([6f3f8fd](https://github.com/ReVanced/revanced-patches/commit/6f3f8fdce05501e4fa4423c2170a916fbea3b199))
* **YouTube:** Combine `Restore old video quality menu` and `Remember video quality` into `Video quality` patch ([#4552](https://github.com/ReVanced/revanced-patches/issues/4552)) ([ee67b76](https://github.com/ReVanced/revanced-patches/commit/ee67b763d5c5947a5b1ef4420b1efa820ed6af83))


### Features

* **Infinity for Reddit:** Add support for package name on IzzyOnDroid ([#4554](https://github.com/ReVanced/revanced-patches/issues/4554)) ([cf9f959](https://github.com/ReVanced/revanced-patches/commit/cf9f959923076c10a7f0a29f6ba277f5a055ec07))
* **Spotify:** Add `Spoof signature` patch ([#4576](https://github.com/ReVanced/revanced-patches/issues/4576)) ([3646c70](https://github.com/ReVanced/revanced-patches/commit/3646c70556b67a6b7ecf9b86869ebf03c3611333))
* **YouTube - Remember video quality:** Add separate Shorts default quality settings ([#4543](https://github.com/ReVanced/revanced-patches/issues/4543)) ([88142ab](https://github.com/ReVanced/revanced-patches/commit/88142ab464192b564b1b8d56a6b45663f77f5e00))



</details>

