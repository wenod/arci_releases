# Arci

The instant launcher for macOS, by [Prayukta](https://prayukta.com). The app grid Apple took
away, with a bar that answers as you type: apps, calculations, units and currencies, time
zones and timers, translation, notes, clipboard history, emoji, and actions you make your own.
Native Swift for Apple silicon. Speed is the product.

**Website and docs: [arci.prayukta.com](https://arci.prayukta.com)**

This repository holds Arci's downloads, one GitHub release per version.

## Download

**[Download Arci.dmg](https://github.com/wenod/arci_releases/releases/latest/download/Arci.dmg)**: always the latest version
(same as [arci.prayukta.com/download](https://arci.prayukta.com/download)).

## Requirements

- macOS 26 or later
- A Mac with Apple silicon (M1 or later). Intel Macs aren't supported.

## Install

1. Open `Arci.dmg`.
2. Drag **Arci** onto **Applications**.
3. Open Arci from Applications. It's signed with a Developer ID and notarized by Apple, so
   macOS opens it after the usual "downloaded from the internet" question.
4. Arci lives in the menu bar, with no Dock icon. The first time, it opens its Settings: press
   the shortcut you want to summon it with, and you're set. When an action needs a permission
   (Accessibility to paste into other apps, for example), Arci asks then.

## Updates

Arci checks for a new version when it starts and once a day. When there is one, it appears in
Settings → General → Updates and at the top of Arci's menu-bar menu. **Install and Relaunch**
downloads it, checks that it's signed by Arci's developer and notarized by Apple, replaces the
app, and opens it again.

Arci can only update itself when it runs from Applications. If it was opened straight from the
disk image or Downloads, it says so. Move it to Applications first.

## Betas

Releases marked **Pre-release** are betas. The Download link above and Arci's updater skip
them. To try one, download `Arci.dmg` from that release and install it as above. When the
next stable version comes out, the updater offers it.

## Going back to an earlier version

Download `Arci.dmg` from an earlier release, quit Arci, and drag the older Arci onto
Applications, choosing **Replace**. The updater never offers an older version, so it will
offer the newest stable version again.

## What's in a release

- `Arci.dmg`: the app, signed, notarized and stapled, in a disk image that's signed, notarized
  and stapled too.
- `latest.json`: what Arci's updater reads: version, build number, the DMG's address and its
  SHA-256 checksum, and the oldest macOS it runs on.

## Help

Questions and problems: [support@prayukta.com](mailto:support@prayukta.com), or see
[arci.prayukta.com/support](https://arci.prayukta.com/support).

Arci's source code is private. This repository holds the downloads only.
