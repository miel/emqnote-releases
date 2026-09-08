# emqnote — releases

Release binaries for **emqnote**, a resident note-taking app that writes plain markdown
files into a folder you already sync. The source lives elsewhere; this repository holds
nothing but the downloads.

## Download

The latest build is on the [releases page](https://github.com/miel/emqnote-releases/releases/latest).

| Platform | File | Install |
|---|---|---|
| Windows 11 (x64) | `emqnote-Setup-<version>.exe` | Per-user installer, no admin rights. Updates itself from this page. |
| macOS (Apple Silicon) | `emqnote-<version>-arm64-mac.zip` | Unzip into `/Applications`. Checks this page for a newer version and tells you; the reinstall is by hand. |

## What it talks to

The app makes two kinds of outbound request and no others: the update check against this
repository, and images fetched when you explicitly paste something that references them.

## Licence

Closed source. Free of charge — free to use, including at work — for every version
numbered below 2.0.0. The full terms ship with the app as `LICENSE.md`.
