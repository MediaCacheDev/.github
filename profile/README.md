# MediaCache

Open-source media libraries for apps and the web: caching, streaming and transparent video, on Android, iOS, React Native and every modern browser.

[mediacache.dev](https://mediacache.dev)

## MediaCache

A universal media cache for every platform and framework, built for video first. It streams while caching, caches partial byte ranges, prefetches the first seconds of a video and handles HLS and DASH, on the web and through AVPlayer and ExoPlayer on mobile. It caches anything else too: images, API responses, any file. A JavaScript core serves the web frameworks, a C++17 core serves native apps, and React Native, Capacitor and Flutter sit on top of both. *Coming soon.*

## Transparent video

Transparent animation that plays the same on every platform, including browsers that can't show transparent video themselves.

| Project | |
|---|---|
| **alpha-video** *(coming soon)* | Transparent video player for Android, iOS, React Native and the web. VP8, VP9 and AV1 WebM with alpha, single- or dual-stream, with hardware decoding where available. |
| **alpha-video-gpu** *(coming soon)* | Transparent animations from ASTC texture arrays in KTX2 files. The GPU draws frames as stored, so dozens play at once with little CPU, in exchange for larger files. |
| **alpha-video-gpu-encoder** *(coming soon)* | The CLI that makes alpha-video-gpu's KTX2 files from PNG sequences or videos. |
| [**react-native-apng-avif**](https://github.com/MediaCacheDev/react-native-apng-avif) | Animated APNG and AVIF with full alpha for React Native on Android, iOS and the web. |
| **alpha-glow-button** *(coming soon)* | A button whose hover and press glow is one pre-rendered transparent animation, played by any of the above. |

alpha-video gives the smallest files. alpha-video-gpu is for screens with many animations at once. APNG and AVIF suit short loops that need no player.

### Earlier work

- [**alpha-video-ffmpegkit**](https://github.com/MediaCacheDev/alpha-video-ffmpegkit): the first attempt at transparent WebM on React Native, on FFmpegKit. Kept as a reference; new apps should use alpha-video.
- [**ffmpegkit-vp9**](https://github.com/MediaCacheDev/ffmpegkit-vp9): a minimal FFmpegKit 6.0 build for Android and iOS that decodes VP9 WebM with alpha through libvpx.

## Support

These libraries are built and maintained by one developer. If they save you time, you can support the work on [Ko-fi](https://ko-fi.com/oftheoverengineer).
