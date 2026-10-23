<p align="center">
  <img src="penguin.png" alt="SingSong penguin" width="160">
</p>

<h1 align="center">SingSong</h1>

<p align="center"><b>Offline Pinoy karaoke for Android tablets, with a phone remote for your guests.</b></p>

<p align="center">Free · For personal use only · Not monetized</p>

---

## What is SingSong?

SingSong turns an Android tablet (or a phone in landscape) into a karaoke player. Songs play with music and
lyrics that light up in time with the melody, over moving background videos. Your guests can join from
their own phones over the same Wi-Fi to search for songs and reserve them, without ever interrupting the
person singing.

It works **fully offline**. The only thing that ever uses the internet is the check for a newer version,
and the app works the same without it.

## Features

- **Karaoke stage:** big outlined lyrics with a red sweep that follows the melody, a 3-2-1 countdown, the
  song's title, artist, and singer's name when it starts, and background videos that keep playing.
- **Song book:** search by title or artist as you type, browse A to Z, or browse by artist.
- **Queue:** reserve songs; "Up Next" shows who is singing next. Start singing when you are ready.
- **Phone remote:** guests scan a QR code (or type the address and a 6-digit code), enter their name, then
  search and add songs. Each guest can skip, remove, or change the key of **only their own** songs.
- **Key and volume:** change the key a semitone at a time, set the volume, lyrics size, and more.
- **Score:** an optional fun score after each song (it does not listen to your singing).
- **FAQs in Tagalog and English**, What's new after each update, and light and dark menus.
- **Updates:** when a newer SingSong is out, the app tells you what changed and offers the download.

## Requirements

| | Minimum | Recommended |
|---|---|---|
| **Android** | 7.0 (Nougat) | 11 or newer |
| **RAM** | 3 GB | 4 GB or more |
| **Free storage** | 2.5 GB while importing, then 1.3 GB | 4 GB or more |
| **Screen** | Phone in landscape | Tablet, 10 inches or larger |
| **Processor** | ARM (32- or 64-bit) or x86-64 | 64-bit ARM |
| **Network** | None (fully offline) | Wi-Fi or the tablet's hotspot for the phone remote |

- **Why this much RAM:** while a song plays, SingSong uses about 550 MB (up to about 650 MB when a song
  opens) for the music engine, the sound bank, the lyrics, and the background video.
- **Storage:** the app itself is about 90 MB. The imported song pack takes about 1 GB (songs about 580 MB,
  background videos about 330 MB, sound bank about 115 MB, song list about 20 MB). While importing, the
  `.zip` also needs room (about 900 MB); you can delete it after the import finishes.
- **A SingSong song pack** (`.zip`) is not included in the app.
- **Phone remote guests** need any phone with a web browser (Android or iPhone) on the same Wi-Fi as the
  tablet, or connected to the tablet's hotspot. Nothing to install.
- Tested on a Redmi Pad Pro 5G (Android 16, 8 GB RAM).

## Install

1. Download the latest `SingSong-<version>.apk` from **Releases** (on the right of this page).
2. Open the downloaded file. If Android asks, allow your browser or file manager to **install unknown
   apps**, then tap **Install**.
3. Open SingSong, tap **Import data**, and choose your SingSong `.zip` song pack (or the folder it was
   unpacked into). Your original files are never changed.
4. Tap **Open Library**, choose a song, and sing.

## Updating

When a new version is out, SingSong shows **"SingSong needs an update"** with its major changes, minor
changes, and bug fixes. Tap **Download**, then open the file to install it over the old one; your songs and
settings stay. Tap **Later** to keep singing; Settings shows a red **1** until you update.

> Updates install over the old app only when they come from this page. Every SingSong release is signed
> with the same key.

## Phone remote

1. On the tablet, tap **Phone remote**, then **Start session**.
2. Guests scan the QR code with their phone camera, or open the address shown and type the 6-digit code.
3. Guests type their name, then search and add songs. Everyone sees who added each song.

If phones cannot open the remote, check that they are on the same Wi-Fi (not mobile data). Some routers
keep devices apart ("AP isolation" or "client isolation"); turn that off, or use the tablet's hotspot.

## Versions

### 1.4.0
- When a song starts, the name of the person who added it from their phone shows in red under the title.
- Credits in Settings and in the FAQs, for the owners of the songs, background videos, sound bank, and fonts.
- Home: "Ready to sing" sits higher, with a reminder that the app is free. Reserved songs are listed below it
  and scroll. Open Library shows only when nothing is reserved; the Phone remote button hides while a session
  is on.
- Updates: "SingSong needs an update" with what changed, Later or Download, and a red 1 on Settings.
- Phone remote: if the tablet's Wi-Fi drops, the remote starts again by itself with the same code, and phones
  reconnect without scanning again.
- Phone remote: a phone with a bad connection can no longer keep the tablet waiting.
- Tested on a tablet: wrong and tricky requests, 150 phones connecting at once, 15 phones searching for two
  minutes, the Wi-Fi turned off and on, and a karaoke night of 20 songs with 10 phones.

### 1.3.3
- Every background video plays to its end, then a different one, until all have played.

### 1.3.2
- Changing the key no longer restarts the music; the song continues in the new key.

### 1.3.1
- When a singer changes their key from their phone, the new key shows briefly on the player.

### 1.3.0
- Change the key of your own song from your phone.
- One phone on its own may reserve up to 15 songs; with two or more phones, 3 each (Settings).
- Turn the score after each song on or off.
- The song menu during a song closes by itself after 5 seconds.

### 1.2.0 – 1.2.1
- FAQs in Tagalog (Taglish) or English.
- Home: Phone remote beside Open Library, with a hand pointing at it.

### 1.1.0 – 1.1.2
- Background videos keep playing through new songs and play in random order, none repeating until all
  have played.
- New FAQs: when the remote won't open on a phone, and whether SingSong needs the internet.

### 1.0.0 – 1.0.1
- The SingSong penguin icon.
- Guests type their name when they join; everyone sees who added each song.
- Change the key with − and + during a song.
- Settings for volume, key, sound bank, lyrics size, lyric delay, and songs per phone.
- Phone remote: search, browse A–Z, artists, Up next, and skip or remove your own songs.
- Offline karaoke with synced lyrics, a song queue, and scores.

## Credits

This app is free and for personal use only. It does not generate any money and is not monetized.

- **Songs (songs.idx, songs.dat):** the original publisher of the karaoke song pack, and the songwriters,
  artists, and arrangers of every song.
- **Background videos:** Platinum Karaoke (videos marked Free To Use), and the owners of the other videos
  flashed during singing.
- **Home background picture:** its original photographer.
- **Sound bank (SingSong.sf2):** GeneralUser GS v2.0.3 by S. Christian Collins (GeneralUser GS License v2.0),
  with the Salamander Grand Piano by Alexander Holm (CC BY 3.0).
- **Fonts:** Figtree by Erik Kennedy (SIL Open Font License 1.1). PapaYo, the lyrics font, by its designer.
- **Music engine:** FluidSynth (LGPL 2.1), through flutter_midi_pro.

<p align="center"><sub>Application Developed and Maintained by emji</sub></p>
