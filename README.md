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

[Horizontal Layout]

<img width="1235" height="793" alt="image" src="https://github.com/user-attachments/assets/45c82486-526f-44eb-8c6c-aea134355fc8" />

[Vertical Layout]

<img width="1235" height="793" alt="image" src="https://github.com/user-attachments/assets/bea5cf35-9b7c-4fdf-b315-d94c3044f681" />

[Minimize Button]
<img width="1228" height="580" alt="image" src="https://github.com/user-attachments/assets/94fb3fe3-3b46-4d20-ac27-d9d1fa6853a9" />


---

## Requirements | Keperluan

- OBS Studio with **WebSocket Server enabled**
- Go to: `Tools > WebSocket Server Settings > Enable WebSocket Server`
- Default port: `4455`

---

## Setup | Cara Guna

1. Enable WebSocket Server in OBS | Hidupkan WebSocket Server dalam OBS
<img width="1235" height="793" alt="image" src="https://github.com/user-attachments/assets/ce15b973-995b-4a83-b510-03afe12b2b5a" />

<img width="677" height="597" alt="image" src="https://github.com/user-attachments/assets/5e334977-26fd-4fec-870f-fa29db5eaa97" />

2. Download custom_browser_toolbar-v1.0.0-beta.html and open file using browser. Copy link address or `ctrl+c`
<img width="1138" height="416" alt="image" src="https://github.com/user-attachments/assets/4261b433-2c5e-476d-87d0-462ca3a9aa66" />

3. Open Docks on OBS > Custom Browser Docks > paste link address to URL section. Dock name put what you like and click Apply.
  
4. Go settings toolbar > Websocket > Enter your WebSocket host, port, and password | Masukkan host, port, dan password
<img width="1235" height="1032" alt="image" src="https://github.com/user-attachments/assets/dcfb05d4-a566-4908-86e3-b5c7a6c705c9" />

5. Connect and control OBS | Sambung dan kawal OBS
`Click connect and if setting closed websocket ready to connected and will show green indicator`

---

## File Structure | Struktur Fail

```
Custom-Browser-Toolbar/
└── custom_browser_toolbar-v1.0.0-beta.html    ← Main file (HTML + CSS + JS)
```

---

## Version | Versi

`v1.0.0-beta`
work on windows and linux - because this run via browser

---

## License

Private — for personal use only | Peribadi — untuk kegunaan sendiri sahaja.
