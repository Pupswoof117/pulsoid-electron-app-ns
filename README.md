# This is unmaintained due to the person who asked me to maintain this cut me off becauwse his friend made a threat of SA and he sided with her

these are left up as an archive

no further work will be done.

-AllisonW

# The above is the mirror from the server hosting historical builds. 
# HRMAPP Pulsoid Discord RPC + OBS Overlay (Electron)

### 1) Install
```bash
npm install
npm run start
```

### 2) Configure
Open **Settings** inside the app:
- Paste your **Pulsoid Access Token** (scope: `data:heart_rate:read`)
- (Optional) Add **Discord Client ID**, then toggle **Discord RPC** on
- Toggle **Realtime** to start/stop Pulsoid streaming

### 3) OBS Overlay
- Click **Open OBS Overlay** in the app
- In OBS → *Sources* → **+** → **Window Capture** → choose the window titled **Overlay**
- Enable **Allow Transparency** if available; ensure the overlay window is visible on the same desktop

> Tip: You can resize the overlay window to taste. It’s click‑through by default.

### Notes
- Settings are saved locally via `electron-store` and loaded at startup
- Discord RPC requires the **Discord desktop** client running on the same machine
- The live chart is capped to the latest ~120 points


### REMINDER

 - Releases (from Pups) are [here](https://webpoweredlab.com/hrmonitor/)
