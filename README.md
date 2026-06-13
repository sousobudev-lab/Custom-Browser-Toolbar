# Custom Browser Toolbar

> A lightweight OBS control toolbar running in the browser via `obs-websocket-js`.  
> Toolbar kawalan OBS yang ringan, berjalan dalam browser menggunakan `obs-websocket-js`.

---

## Overview | Gambaran Keseluruhan

**EN:** A single-file HTML toolbar that connects to OBS Studio via WebSocket. Designed for use as a browser dock or custom browser source inside OBS.

**MY:** Toolbar dalam satu fail HTML yang bersambung ke OBS Studio melalui WebSocket. Direka untuk digunakan sebagai browser dock atau custom browser source dalam OBS.

---

## Features | Ciri-ciri

- Scene switching | Tukar scene
- Studio Mode toggle
- Virtual Camera toggle
- Replay Buffer control
- Horizontal / Vertical / Auto layout
- Hold source button to view Source Properties | Tahan butang source untuk lihat Properties source
- Shortcut / Hotkey support

---

## Requirements | Keperluan

- OBS Studio with **WebSocket Server enabled**
- Go to: `Tools > WebSocket Server Settings > Enable WebSocket Server`
- Default port: `4455`

---

## Setup | Cara Guna

1. Enable WebSocket Server in OBS | Hidupkan WebSocket Server dalam OBS
2. Open `toolbar.html` in browser | Buka `toolbar.html` dalam browser
3. Enter your WebSocket host, port, and password | Masukkan host, port, dan password
4. Connect and control OBS | Sambung dan kawal OBS

---

## File Structure | Struktur Fail

```
Custom-Browser-Toolbar/
└── toolbar.html    ← Main file (HTML + CSS + JS)
```

---

## Version | Versi

`v1.0.0-beta`

---

## License

Private — for personal use only | Peribadi — untuk kegunaan sendiri sahaja.
