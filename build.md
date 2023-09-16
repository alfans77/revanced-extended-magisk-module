YouTube: 18.35.36  
Music (arm64-v8a): 6.19.51  
Music (arm-v7a): 6.19.51  


Install [mMicroG](https://github.com/inotia00/mMicroG/releases) (recommended), [Vanced Extended MicroG](https://github.com/inotia00/VancedMicroG/releases) or [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases) to be able to use non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-3.1.2-all.jar  
Integrations: inotia00/revanced-integrations-0.117.4.apk  
Patches: inotia00/revanced-patches-2.190.4.jar  

YouTube
==
- fix(youtube/bypass-ambient-mode-restrictions): update fingerprint
- fix(youtube/default-video-quality): default video quality is not applied at cold start
- fix(youtube/hide-suggestions-shelf): not working on tablets https://github.com/inotia00/ReVanced_Extended/issues/1337
- fix(youtube/sponsorblock): change invalid patch name
- fix(youtube/sponsorblock): fetch to latest source
- fix(youtube/spoof-player-parameters): spoofing also applies to shorts videos
- fix(youtube/settings): remove unused string resources
- feat(youtube/translations): update translation
`Korean`, `Vietnamese`


YouTube Music
==
- feat(music): add `replace-dismiss-queue` patch
- feat(music): add `sponsorblock` patch https://github.com/inotia00/ReVanced_Extended/issues/97
- feat(music): add support version `v6.19.51`
- feat(music/hide-flyout-panel): code refactoring
- fix(music/enable-new-layout): change patch description
- fix(music/hook-download-button): change the default external downloader package name https://github.com/inotia00/ReVanced_Extended/issues/1340
- fix(music/hook-download-button): download button not hooked in certain situations
- fix(music/spoof-app-version): add missing dependencies
- refactor(music/settings): integrate the preferences of the `return-youtube-dislike` setting into the existing settings
- feat(music/translations): update translation
`Brazilian`, `Dutch`, `French`, `Japanese`, `Korean`, `Polish`, `Russia`, `Spanish`, `Turkish`, `Vietnamese`


Etc
==
- build: update dependency


※ Compatible ReVanced Manager: [RVX Manager v1.9.7 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.9.7)
---
CLI: inotia00/revanced-cli-3.1.2-all.jar  
Integrations: YT-Advanced/revanced-integrations-0.119.1.apk  
Patches: YT-Advanced/revanced-patches-2.190.2.jar  

### [2.190.2](https://github.com/YT-Advanced/ReX-patches/compare/v2.190.1...v2.190.2) (2023-09-11)

# YouTube
- **feat(youtube)**: add support version `v18.35.36`
- **fix(youtube/whitelist)**: SponsorBlock option disappear
- **fix(youtube/hide-quality-footer)**: Not getting hidden
---  
