# HyperSuperCat

An utterly unhelpful alien cat for your Mac **and Windows PC**.

This repository hosts release binaries and instructions only. Application source is not published here.

## Download / 다운로드

[Get the latest release / 최신 버전 다운로드](https://github.com/snctjunyong-ctrl/update/releases/latest)

- **HyperSuperCat-Mac.zip** — macOS 14+ on Apple Silicon. Extract and move the app to Applications.
- **HyperSuperCat-Windows.zip** — Windows 11 / Windows 10 22H2, x64 Intel/AMD. Extract the entire ZIP, then run HyperSuperCat.exe. The .NET runtime is included; no administrator access is required.

Use the alien cat icon in the Mac menu bar or Windows system tray (possibly under the ^ arrow) for settings and Quit.

Mac은 메뉴 막대, Windows는 작업 표시줄 알림 영역의 고양이 아이콘을 누르면 설정/종료가 가능합니다. Windows ZIP은 전체 압축 해제 후 EXE를 실행하세요.

## First-run warnings / 실행 안내

Mac is ad-hoc signed but **not Apple-notarized**. If you trust its source and macOS offers the option, use System Settings → Privacy & Security → Open Anyway for this app. [Apple instructions](https://support.apple.com/102445).

Windows is **unsigned**. SmartScreen may display an unrecognized-app warning. Only if you trust the source and the option is offered, use More info → Run anyway for this app. Smart App Control or managed policies may prevent launch. [Microsoft guidance](https://learn.microsoft.com/en-us/windows/apps/package-and-deploy/smartscreen-reputation).

Do not disable system security. If malware is detected, do not run the file; report the warning.

## Validation status

**The initial Windows build is cross-compiled and core-tested on a Mac, but has not been run on a Windows PC.** Tray interactions, transparency, dragging and mixed-DPI displays still need Windows runtime validation. Mac build, core tests and bundle-signature checks pass; complete desktop interaction validation was also unavailable in the build environment. Read the release notes and included test checklist.

Windows 첫 빌드는 실제 Windows PC에서 아직 실행 검증하지 않았습니다. 테스트 범위와 제한 사항을 릴리스 설명에서 확인해주세요.

## Features

Alien/normal cat transformations, laser effects, sketch UFO teleport escapes, 50:50 click-to-catch, dragging, useless daily reports, optional startup, pause/hide and settings. Platform-specific motion, sounds and menu appearance may differ.

Languages: English, 한국어, 日本語, 简体中文, 繁體中文, Español, Français, Deutsch. Automatically follows the system language, with a manual override.

## Updates

While running, the app checks this public repository at most once a day. Automatic checks can be disabled; manual checks are available. Only releases containing the ZIP for the current OS qualify. Downloads and app replacement are manual, not automatic installation. No notifications are sent while the app is closed. No usage statistics or GitHub credentials are sent.

## Feed the alien cat

[Optional food supplies / 에일리언캣에게 식량 공급하기](https://ko-fi.com/hypersupercat)

## Notion distribution

Use the stable latest-release link above for your Notion download button. It shows both Mac and Windows assets, so the Notion link does not need changing for every version.
