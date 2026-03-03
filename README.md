# MediaInfo

___Convenient unified display of the most relevant technical and tag data for video and audio files___

MediaInfo is a convenient unified display of the most relevant technical and tag data for video and audio files.

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```bash
flatpak install flathub net.mediaarea.MediaInfo
flatpak run net.mediaarea.MediaInfo
```

## Building

```bash
git clone git@github.com:flathub/net.mediaarea.MediaInfo.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install net.mediaarea.MediaInfo.json
```
