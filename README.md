# Avatar-Forever Project Page

Official project page for **Avatar-Forever: Decoupled Parallel Training for High-Quality Real-Time Infinite Avatars**.

**Website:** https://leeruibin.github.io/avatarforever-project-page/

The page presents:

- 67 model inference results spanning talking, emotion, cinematic shots, singing, conversation, animals, and general scenes;
- three short-video and three long-video comparison cases across six methods;
- an extended 11-minute continuous generation result;
- the method overview and headline streaming results.

Videos are rendered from `assets/videos/manifest.json` and loaded only after the viewer presses play. Poster images keep the initial page load lightweight.

## Refreshing the video library

Place MP4 files under the matching folders in `assets/videos/`, then run:

```powershell
python tools/build_video_library.py
```

The script rebuilds the manifest and extracts a JPEG poster for each video. Keep filenames and paths URL-safe because GitHub Pages is case-sensitive.
