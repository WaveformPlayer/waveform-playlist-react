> [!IMPORTANT]
> **Replaced by [`@arraypress/waveform-react`](https://www.npmjs.com/package/@arraypress/waveform-react) 2.0.** Import from `@arraypress/waveform-react/playlist` instead — one package per framework, with a sub-path per component ([repo](https://github.com/WaveformPlayer/react), [migration guide](https://docs.waveformplayer.com/getting-started/migrating-from-1x/)).
> This repository is archived and the npm package is deprecated; its 1.x releases keep working.

<div align="center">

# Waveform Playlist for React

**React component wrapper for `@arraypress/waveform-playlist`.**
Declarative `tracks` array, typed props, and an imperative ref handle for playlist and chapter navigation.

[![npm version](https://img.shields.io/npm/v/@arraypress/waveform-playlist-react?style=flat-square&labelColor=09090b&color=3f3f46)](https://www.npmjs.com/package/@arraypress/waveform-playlist-react)
[![license](https://img.shields.io/npm/l/@arraypress/waveform-playlist-react?style=flat-square&labelColor=09090b&color=3f3f46)](https://github.com/WaveformPlayer/waveform-playlist-react/blob/main/LICENSE)

**[Documentation](https://docs.waveformplayer.com/)** · [npm](https://www.npmjs.com/package/@arraypress/waveform-playlist-react)

</div>

---

## Install

```bash
npm install @arraypress/waveform-playlist-react @arraypress/waveform-playlist @arraypress/waveform-player react
```

```tsx
import { WaveformPlaylist } from '@arraypress/waveform-playlist-react';

<WaveformPlaylist tracks={[{ url: '/a.mp3', title: 'A', artist: 'Artist' }]} />
```

## Documentation

Every option, prop, and pattern lives in the docs.

### -> [docs.waveformplayer.com](https://docs.waveformplayer.com/)

[React guide](https://docs.waveformplayer.com/frameworks/react/) — install, props, the imperative API, and SSR notes. All four React wrappers (player / bar / playlist) are on that page.

## License

MIT © [ArrayPress](https://github.com/arraypress)
