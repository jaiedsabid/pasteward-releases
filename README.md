<p align="center">
  <a href="images/AppIcon.png"><img src="images/AppIcon.png" alt="Pasteward app icon" width="128" height="128"></a>
</p>

<h1 align="center">Pasteward</h1>

<p align="center">
  <b>Everything you copy, searchable and one keystroke from pasting.</b><br>
  A quiet, private clipboard manager for the Mac menu bar.
</p>

<p align="center">
  <a href="https://github.com/jaiedsabid/pasteward-releases/releases/latest"><img src="images/download-macos.svg" alt="Download for macOS" width="300"></a>
</p>

<p align="center">
  <a href="https://github.com/jaiedsabid/pasteward-releases/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/jaiedsabid/pasteward-releases?label=release&color=3b7bff"></a>
  <img alt="macOS 14 or later" src="https://img.shields.io/badge/macOS-14%2B-lightgrey">
  <img alt="Apple silicon" src="https://img.shields.io/badge/Apple%20silicon-M1%20and%20later-lightgrey">
  <a href="https://github.com/jaiedsabid/pasteward-releases/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/jaiedsabid/pasteward-releases/total?color=3b7bff"></a>
</p>

<p align="center">
  <a href="images/hero.png"><img src="images/hero.png" alt="Pasteward's main window: every clip in a searchable grid, with collections, categories and types in the sidebar" width="100%"></a>
</p>

## Why Pasteward

macOS remembers one thing at a time. Pasteward remembers all of it, keeps it on your Mac, and gets it back to you faster than you can find it again.

- ✅ **Native and fast.** A small menu bar app written in Swift. Opening a page of clips takes a fraction of a millisecond with 20,000 clips in history; idle, it uses about 0.1% CPU.
- ✅ **Private by construction.** No account, no cloud, no analytics, no tracking. Your history lives in a local database that only you can read.
- ✅ **Passwords never saved.** Anything a password manager marks as secret, plus API keys, private keys, tokens and card numbers, is skipped.
- ✅ **A Quick Panel that stays out of your way.** It slides in without taking the keyboard from the app you are typing in.
- ✅ **Suggestions that explain themselves.** The clips you are most likely to paste next appear on top, each with a plain reason.
- ✅ **Search that understands you.** Instant, forgiving, with operators like `app:Safari type:link after:2026-10-01`.
- ✅ **Paste the way you want.** Plain text, 50 built-in text transforms, bulk paste and paste stacks.
- ✅ **Automatic backups** of your history, with one-click restore.
- ✅ **Pay once.** A lifetime license, no subscription.

## Quick Panel

Press **⇧⌘V** from any app. The panel opens beside what you are doing without stealing focus: pick a clip with the arrow keys, press **↩**, and it pastes. Dock it to any screen edge, float it, or open it at your pointer or text cursor.

<p align="center">
  <a href="images/quick-panel.png"><img src="images/quick-panel.png" alt="The Quick Panel docked to the right edge, in dark mode" width="300"></a>
  &nbsp;&nbsp;
  <a href="images/quick-panel-light.png"><img src="images/quick-panel-light.png" alt="The Quick Panel in light mode" width="300"></a>
</p>

- Chips under the search bar filter by collection, favorites, type, app or date, and by categories you define.
- Drag a clip into another app, hover for a full preview, or press **⌥1 – ⌥5** to paste one of the suggestions straight away.
- Prefer a strip? Dock it to the bottom or top of the screen.

<p align="center">
  <a href="images/quick-bar.png"><img src="images/quick-bar.png" alt="The Quick Panel docked along the bottom of the screen" width="100%"></a>
</p>

## Suggestions

The clips you are most likely to paste next sit above your history, each with a reason you can read: *Pasted in Safari 6 times*, *Just copied*, *Often used*. Pasteward learns where you paste on your Mac only, and never reads or stores what you copied to do it.

<p align="center">
  <a href="images/suggestions.png"><img src="images/suggestions.png" alt="Suggested clips above the history, each with the reason it was picked" width="300"></a>
</p>

Suggestions are part of the paid plans.

## Paste Stack

Copy a series of things, then paste them one after another, or all at once. With the stack collecting, **⌘V** in any app pastes the next clip. Keep several stacks, reorder them by dragging, and join clips with a new line, a space, a comma or your own separator.

<p align="center">
  <a href="images/paste-stack.png"><img src="images/paste-stack.png" alt="The Paste Stack window with five queued clips and Paste All" width="300"></a>
</p>

## Organize without effort

- **Collections** with their own colors and icons.
- **Favorites, pins and aliases**: give a clip a short name and type it to find it.
- **Categories**: rules that sort clips for you, including "looks like code".
- **Search operators**: `app:`, `type:`, `col:`, `alias:`, `after:`, `before:`, `fav:true`, `pinned:true`, `-word` and `"exact phrase"`.

## Install

**Requirements:** a Mac with Apple silicon (M1 or later) running macOS 14 (Sonoma) or later.

1. Download `Pasteward-<version>.dmg` from the [latest release](https://github.com/jaiedsabid/pasteward-releases/releases/latest).
2. Open it and drag **Pasteward** to **Applications**.
3. Open Pasteward. It lives in your menu bar.
4. macOS may say it can't verify the app, because releases are not yet notarized by Apple. You confirm once:
   - **macOS 15 (Sequoia) or later:** double-click Pasteward and click **Done**. Then open **System Settings → Privacy & Security**, scroll to **Security**, click **Open Anyway** next to "Pasteward was blocked", and confirm with your password or Touch ID.
   - **macOS 14 (Sonoma):** right-click Pasteward in Applications, choose **Open**, then **Open** again.
   - **Any version, from Terminal:** `xattr -dr com.apple.quarantine /Applications/Pasteward.app`
5. When asked, allow Pasteward under **System Settings → Privacy & Security → Accessibility**. That is what lets it paste for you. Without it, clips are still copied and you press ⌘V yourself.

Every download is listed with its SHA-256 checksum in `SHA256SUMS.txt` on the release page.

### Updates

Choose **Settings → General → Software update → Check for Updates…**, or switch on automatic checks there. Updates are signed, and Pasteward verifies the signature before installing anything.

## Plans

Pasteward is free to try for 14 days. After that it needs a lifetime license: one payment, valid for as many devices as your plan includes.

| Plan | Devices | Support | Price |
|---|---|---|---|
| **Standard** | 2 | Standard | $20 |
| **Pro** | 5 | Priority | $30 |
| **Family** | 15 | Priority | $50 |

**Buy:** [**Polar** (choose a plan)](https://buy.polar.sh/polar_cl_0Xz9c53Kl8Bs878gLGWruF0nCSLtynFgMloli3Ivrk9) · [**Lemon Squeezy** (choose a plan)](https://jaiedsabid.lemonsqueezy.com)

After you buy, open **Settings → License**, choose the site you bought from, paste your key and click **Activate**. To move a license to another Mac, click **Deactivate This Mac** first.

**The trial** shows your newest 25 clips (older ones are kept and return with a license), and includes 1 custom category, 1 custom collection and 9 Paste Stack uses. Suggestions need a license.

## Privacy

- Your history is stored in `~/Library/Application Support/Pasteward`, readable only by you. It is never uploaded.
- No analytics, no crash reporting, no account, no ads.
- The only network use is optional and visible: link previews for links you copied (you can turn them off), the update check when you press it, and checking your license key with the site you bought it from (Polar or Lemon Squeezy), about once a week after you activate.
- Concealed items from password managers, API keys, private keys, tokens and card numbers are skipped. You can also ignore whole apps.

## Support

- **Something wrong?** [Open an issue](https://github.com/jaiedsabid/pasteward-releases/issues/new/choose). Include your macOS version, the Pasteward version (shown in the release you downloaded), and what you expected.
- **Idea?** Open an issue too.
- **License problems and refunds** (a key that won't activate, a purchase you want refunded): email contact@devscrate.com with the address you bought with and the site you bought from (Polar or Lemon Squeezy). Please don't post your key in an issue.

This repository holds the downloads and the update feed. The source code is not published here.

---

<p align="center"><sub>© 2026 Pasteward. All rights reserved.</sub></p>
