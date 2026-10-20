<div align="center">

# 🎵 Media Player Homepage for Browser

**A clean, customisable browser homepage that shows what you're listening to on Spotify, with a spinning vinyl, live visualizer, and a smart search bar.**

![Free](https://img.shields.io/badge/price-free-2ea44f) ![No install](https://img.shields.io/badge/homepage-no%20download-blue) ![Browsers](https://img.shields.io/badge/browsers-Chrome%20%7C%20Edge%20%7C%20Firefox%20%7C%20Safari%20%7C%20Brave-lightgrey) ![Powered by Last.fm](https://img.shields.io/badge/powered%20by-Last.fm-d51007)

### [▶ Open the live homepage](https://ryanladdy.github.io/Mediaplayer-Homepage-For-Browser/)

</div>

---

## Overview

This is a free website you can use as your browser's **homepage** and **new tab page**. It reads your listening activity from [Last.fm](https://www.last.fm/) (which tracks Spotify) and turns it into a music dashboard: album art, a spinning vinyl or CD, the song title, and whether it is **playing**, **paused** or **stopped**.

- **Free.** No account with us, no subscription, no ads.
- **Nothing to download for the homepage.** It is a normal web page. Open the link and it works.
- **Works in any modern browser.** Chrome, Edge, Firefox, Safari, Brave, Vivaldi, Opera.
- **Private.** Your settings stay in your own browser (see [Privacy](#-privacy)).

## ✨ Features

| | |
|---|---|
| 🎧 **Now playing** | Song, artist, album and live status (Playing / Paused / Stopped). Keeps showing the song you paused. |
| 💿 **Vinyl or CD** | Spinning record with 3D mouse tilt, album cover, and smooth song-change transitions. |
| 📊 **Visualizer** | 10 styles (bars, wave, orb, ripples and more). Drag it anywhere, resize it, or turn it off. |
| 🔎 **Smart search bar** | Search suggestions, inline autofill, a built-in calculator, engine shortcuts (`gh react`, `y lofi`, `m cafes`), search history, voice search. |
| 🧩 **Widgets** | Clock, weather, quick links, notes, to-do list, focus timer, countdown, world clock, calendar, daily quote. |
| 🎨 **Customisable** | Themes, colour controls (brightness, contrast, gamma, hue, saturation), layouts, fonts, backgrounds, particles. |
| 🔌 **Everything is optional** | Every feature has its own on/off switch in the settings panel. |

## 🚀 Quick start (about 3 minutes)

### 1. Get a free Last.fm account
Sign up at **[last.fm/join](https://www.last.fm/join)**.

### 2. Connect Spotify to Last.fm
Go to **[Settings → Applications](https://www.last.fm/settings/applications)** and connect Spotify. This is what lets the homepage know what you are playing.

### 3. Create a free API key
Visit **[last.fm/api/account/create](https://www.last.fm/api/account/create)** and fill in the form. The name and description can be anything. Leave *Callback URL* empty. For *Application homepage*, enter any web address (for example `https://www.last.fm`). Copy the **API key** you are shown.

### 4. Open the homepage and enter your details
Open the **[live homepage](https://ryanladdy.github.io/Mediaplayer-Homepage-For-Browser/)**. The settings panel opens on the right: enter your **Last.fm username** and **API key**. Play a song on Spotify and it appears within a few seconds.

> Tip: click the sliders icon in the bottom-right corner (or press `,`) to reopen settings at any time.

### 5. Make it your homepage and new tab
Follow the section for your browser below.

---

## 🌐 Set it as your homepage and new tab

Use this address everywhere:

```
https://ryanladdy.github.io/Mediaplayer-Homepage-For-Browser/
```

### Homepage (no extension needed in any browser)

| Browser | Steps |
|---|---|
| **Chrome** | Settings → Appearance → turn on *Show home button* → choose *Enter custom web address* and paste the link. For startup: Settings → On startup → *Open a specific page*. |
| **Edge** | Settings → Start, home, and new tabs → *Home button* → *Set these pages*; and *When Edge starts* → *Open these pages*. |
| **Firefox** | Settings → Home → *Homepage and new windows* → *Custom URLs* → paste the link. |
| **Safari** | Settings → General → *Homepage* → paste the link. |
| **Brave / Vivaldi / Opera** | Settings → search for "home" or "startup" and set a custom page. |

### New tab page

Some browsers can do this on their own; others need one small **free** extension from the browser's official store.

| Browser | How |
|---|---|
| **Safari** | Settings → General → *New tabs open with* → **Homepage**. Nothing to install. |
| **Brave** | Settings → Appearance → *New Tab page shows* → **Homepage**. Nothing to install. |
| **Vivaldi** | Settings → Tabs → New Tab Page → **Specific page**. Nothing to install. |
| **Firefox** | Install the free add-on **[New Tab Override](https://addons.mozilla.org/en-US/firefox/addon/new-tab-override/)**, enter the link, and tick **"Set focus to web page content"** so you can type straight into the page's search bar. |
| **Chrome / Edge / Opera** | Install a free new-tab redirect extension such as **New Tab Redirect** from the Chrome Web Store, open its options, and enter the link (include `https://`). |

Menu names can differ slightly between browser versions.

### Optional: open it as an app, with no address bar

Chrome and Edge can run the homepage in its own clean window with **no tabs and no address bar**, which also avoids the address-bar focus issue below.

1. Open the homepage.
2. Chrome: menu → *Cast, save, and share* → *Install page as app*. Edge: menu → *Apps* → *Install this site as an app*.
3. Launch it from your Start menu or desktop.

For a shortcut that always starts fullscreen, add this to the shortcut's *Target*:
`--app=https://ryanladdy.github.io/Mediaplayer-Homepage-For-Browser/ --start-fullscreen`

---

## 🔒 Privacy

- Your Last.fm username, API key and all settings are saved **only in your own browser** (local storage) and are never stored in this repository.
- The page contacts Last.fm to read your listening activity. Other optional lookups: search suggestions (Google, DuckDuckGo or Wikipedia), weather (Open-Meteo), and website icons for quick links (Google). Turn off the matching feature in settings to stop them.
- **Never commit your API key to a public repository.** You don't need to: you enter it in the page, not in the code.

## ❓ Troubleshooting

<details>
<summary><b>🎵 My Spotify listening activity isn't showing</b></summary>

- Check Spotify is connected at [last.fm/settings/applications](https://www.last.fm/settings/applications).
- Spotify **private sessions** are not tracked by Last.fm. Turn private session off.
- In your Last.fm privacy settings, make sure recent listening is not hidden.
- Confirm the username is spelled exactly as on your Last.fm profile, then check that your profile page shows "Scrobbling now".
- Last.fm can take a few seconds to notice a new song. Lower *Check music every* in settings for faster updates.
</details>

<details>
<summary><b>🔑 My API key isn't working</b></summary>

- Copy the **API key**, not the *shared secret*, and check for extra spaces.
- Re-enter the key in settings (the key field is hidden by default).
- If the status line shows an error message, it comes from Last.fm and says what is wrong.
</details>

<details>
<summary><b>🌐 My homepage isn't opening in a new tab</b></summary>

- Include `https://` at the start of the address in the extension's options.
- Restart the browser after installing the extension.
- Some browsers keep their own new tab page until the extension is allowed to run. Check *Manage extensions*.
</details>

<details>
<summary><b>⌨️ The browser's address bar is selected instead of the page's search bar</b></summary>

Browsers deliberately put the cursor in the address bar on every new tab, and a web page cannot override that. Options:

- **Firefox:** use New Tab Override with *Set focus to web page content* ticked.
- **Chrome / Edge:** extensions that redirect new tabs usually cannot change this. Use the **installed app window** above, or click the page once and start typing (the page sends your typing to its search bar).
- Use the homepage button (Alt+Home) instead of a new tab.
</details>

## 💡 Requirements

- A Spotify account and a Last.fm account linked together
- A free Last.fm API key
- Any modern browser
- A free new-tab extension, only if your browser can't set a custom new tab page itself

## 🛠 Host your own copy (optional)

Fork this repository, then go to **Settings → Pages**, choose the main branch, and GitHub will host your own copy for free.

## ❤️ Credits

Built for music lovers who want their listening right on their browser homepage. Powered by [Last.fm](https://www.last.fm/) and [Spotify](https://www.spotify.com/). If you enjoy the project, please give the repository a ⭐.
