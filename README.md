<div align="center">
---

# 🎵 Media Player Homepage for Browser

**A homepage for your browser that shows what you're listening to on Spotify, with a spinning vinyl, a visualizer and a search bar that actually does stuff.**

![Free](https://img.shields.io/badge/price-free-2ea44f) ![No install](https://img.shields.io/badge/homepage-no%20download-blue) ![Browsers](https://img.shields.io/badge/browsers-Chrome%20%7C%20Edge%20%7C%20Firefox%20%7C%20Safari%20%7C%20Brave-lightgrey) ![Powered by Last.fm](https://img.shields.io/badge/powered%20by-Last.fm-d51007)

### [▶ Open the live homepage](https://ryanladdy.github.io/Mediaplayer-Homepage-For-Browser/)

</div>

---

## What is this?

Its a free website you can set as your browser's homepage and new tab. It grabs what you're playing from [Last.fm](https://www.last.fm/) (which tracks your Spotify) and shows it as a little music dashboard with the album art, a spinning vinyl or CD, the song name, and whether its playing, paused or stopped.

- **Free.** No ads, no subscription, no accounts with me, nothing.
- **Nothing to download for the homepage.** Its just a website, open the link and it works.
- **Works in any modern browser.** Chrome, Edge, Firefox, Safari, Brave, Vivaldi, Opera.
- **Private.** Your stuff is saved in your own browser only (more on that in [Privacy](#-privacy)).

## ⚙️ How to open the settings

There is no settings button on the page, i wanted it clean. Instead you can:

- **Right click** anywhere on the page, or
- Press **Ctrl + .** (Ctrl and the full stop key)

Do it again to close it. You can change that shortcut in the settings (the "Hotkeys and controls" part), and if you would rather have a button back there is a switch for it too.

---

## ✨ Features

Every single one of these has its own on/off switch, so turn on what you like and leave the rest.

**Music**
- Now playing with live status (Playing / Paused / Stopped), it keeps showing the song you paused
- Spinning vinyl or CD, 3D tilt with your mouse, smooth song change animations
- Visualizer with 10 styles, you can drag it anywhere, resize it, or write your own
- **Listening clock** (when in the day you listen the most)
- **Listening calendar** (the green squares thing but for your music, with streaks)
- **On this day** (what you were playing 1, 2 and 5 years ago)
- **Taste match** (compare with a friend's Last.fm)
- **Artist galaxy** (your top artists floating in 3D, drag to spin it)
- **Commit vinyl** (the grooves on the record come from your GitHub commits)
- **Streamer overlay** for OBS

**Search**
- Suggestions, autofill like the address bar, a calculator, search history, voice search
- Shortcuts, type `gh react`, `y lofi`, `m cafes` and so on

**Look and feel**
- **Live sky** background that matches the real sun, moon and weather where you are
- **Newspaper mode** (yes really)
- Themes, colours, gamma, hue, fonts, particles, layouts, gradients and your own image
- Share your setup with a link

**Extras**
- Clock, weather, quick links, notes, to-do list, focus timer, countdown, world clock, calendar, quote
- **Soundscapes** (rain, wind, ocean, cafe, white and brown noise)
- **Repo radio** (turns a GitHub repo's commits into music)
- **Weather music** (calm music that changes with the weather)

## 🚀 Quick start (about 3 minutes)

### 1. Make a free Last.fm account
**[last.fm/join](https://www.last.fm/join)**

### 2. Connect Spotify to Last.fm
**[Settings → Applications](https://www.last.fm/settings/applications)**. This is how the homepage knows what you're playing.

### 3. Get a free API key
**[last.fm/api/account/create](https://www.last.fm/api/account/create)**. Name and description can be anything, leave *Callback URL* empty, and for *Application homepage* put any web address (like `https://www.last.fm`). Copy the **API key** it gives you.

### 4. Put your details in
Open the **[live homepage](https://ryanladdy.github.io/Mediaplayer-Homepage-For-Browser/)**, the settings open on their own the first time. Type in your **Last.fm username** and **API key**, play a song on Spotify and it shows up in a few seconds.

### 5. Make it your homepage and new tab
Check your browser below.

---

## 🌐 Set it as your homepage and new tab

Use this link everywhere:

```
https://ryanladdy.github.io/Mediaplayer-Homepage-For-Browser/
```

### Homepage (no extension needed)

| Browser | Steps |
|---|---|
| **Chrome** | Settings → Appearance → turn on *Show home button* → *Enter custom web address* and paste the link. For startup: Settings → On startup → *Open a specific page*. |
| **Edge** | Settings → Start, home, and new tabs → *Home button* → *Set these pages*, and *When Edge starts* → *Open these pages*. |
| **Firefox** | Settings → Home → *Homepage and new windows* → *Custom URLs* → paste the link. |
| **Safari** | Settings → General → *Homepage* → paste the link. |
| **Brave / Vivaldi / Opera** | Settings → search "home" or "startup" and set a custom page. |

### New tab page

Some browsers can do it by themselves, others need one small free extension from the official store.

| Browser | How |
|---|---|
| **Safari** | Settings → General → *New tabs open with* → **Homepage**. |
| **Brave** | Settings → Appearance → *New Tab page shows* → **Homepage**. |
| **Vivaldi** | Settings → Tabs → New Tab Page → **Specific page**. |
| **Firefox** | Add-on **[New Tab Override](https://addons.mozilla.org/en-US/firefox/addon/new-tab-override/)**, put in the link, and tick **"Set focus to web page content"** so you can type straight into the page's search bar. |
| **Chrome / Edge / Opera** | A new tab redirect extension like **New Tab Redirect** from the Chrome Web Store, put the link in its options (with `https://`). |

Menu names can be a little different depending on your browser version.

### Optional: open it as an app (no address bar)

Chrome and Edge can open the homepage in its own clean window with no tabs and no address bar.

1. Open the homepage
2. Chrome: menu → *Cast, save, and share* → *Install page as app*. Edge: menu → *Apps* → *Install this site as an app*
3. Open it from your Start menu or desktop

Want it fullscreen every time? Add this to the end of the shortcut's *Target*:
`--app=https://ryanladdy.github.io/Mediaplayer-Homepage-For-Browser/ --start-fullscreen`

---

## 🎥 For streamers (OBS overlay)

In the settings open **Streamer overlay (OBS)**, pick what you want to show, press **Copy overlay link** and add it to OBS as a *Browser Source*. It gives you a clean now playing box with a see through background.

> ⚠️ That link has your API key inside it so don't share it or post it anywhere.

## 🎨 Make your own themes and visualizers

This is the part i would love people to help with. In the repo there are two files:

- `themes.json` for colour themes
- `visualizers.json` for visualizer code

Add yours, send a pull request, and they show up in the settings for everyone. You can also paste your own visualizer code straight into the settings (only paste code you trust).

## 🔒 Privacy

- Your Last.fm username, API key and settings are saved **only in your own browser** and never in this repo.
- The page talks to Last.fm to get your music. Some optional features also use other free services: search suggestions (Google, DuckDuckGo or Wikipedia), weather (Open-Meteo), website icons (Google) and GitHub (commit vinyl and repo radio). Turn the feature off in the settings and it stops.
- **Never put your API key in the code or commit it to GitHub.** You dont need to, you type it into the page.

## ❓ Troubleshooting

<details>
<summary><b>🎵 My Spotify listening isn't showing</b></summary>

- Make sure Spotify is connected at [last.fm/settings/applications](https://www.last.fm/settings/applications)
- Spotify **private sessions** don't get tracked, turn it off
- In your Last.fm privacy settings make sure your recent listening isn't hidden
- Check your username is spelled exactly like your Last.fm profile
- Last.fm takes a few seconds to notice a new song, you can lower *Check music every* in the settings
</details>

<details>
<summary><b>🔑 My API key isn't working</b></summary>

- Copy the **API key**, not the *shared secret*, and check there are no spaces
- Type it into the settings again
- If the status line shows an error, that message comes from Last.fm and tells you whats wrong
</details>

<details>
<summary><b>⚙️ I can't find the settings</b></summary>

Right click the page or press **Ctrl + .** If neither works, check the right click setting wasn't turned off, or change the shortcut. Some browser shortcuts (like Ctrl+T or Ctrl+W) can't be used by websites, so pick a different combo if yours does nothing.
</details>

<details>
<summary><b>🌐 My homepage isn't opening in a new tab</b></summary>

- Put `https://` at the start of the link in the extension's options
- Restart your browser after installing the extension
- Check the extension is allowed to run in *Manage extensions*
</details>

<details>
<summary><b>⌨️ The browser's address bar is selected instead of the page's search bar</b></summary>

Browsers always put the cursor in the address bar on a new tab and websites can't change that. You can:

- **Firefox:** use New Tab Override with *Set focus to web page content* ticked
- **Chrome / Edge:** use the installed app window above, or just click the page once and start typing, it sends your typing to its search bar
- Use the home button (Alt+Home) instead of a new tab
</details>

<details>
<summary><b>🐙 Commit vinyl or repo radio isn't loading</b></summary>

GitHub only lets a page ask about 60 times an hour without logging in, so if you refresh a lot it can run out for a bit. Also check the username or repo is spelled right (repo looks like `owner/name`).
</details>

## 💡 What you need

- A Spotify account and a Last.fm account linked together
- A free Last.fm API key
- Any modern browser
- A free new tab extension, only if your browser can't set a custom new tab by itself

## 🛠 Host your own copy

Fork the repo, go to **Settings → Pages**, pick the main branch and GitHub hosts your copy for free.

## ❤️ Credits

Made for anyone who wants their music on their homepage. Powered by [Last.fm](https://www.last.fm/) and [Spotify](https://www.spotify.com/). If you like it a ⭐ on the repo would mean a lot, and if you use any of it just mention me in your readme, thats all i ask.

---

## ℹ️ Extra info

## my work isnt fully created by me ive had help with this project, I have no problems with anybody forking this repo and creating things from my project, i would be so grateful if people used my work, And if u do use any of my work maybe just mention me somewhere just in a readme file nothing special, I will also never ask anybody to pay for any of my work all of this is free i want to give this out for more people to grow and create greater things.
