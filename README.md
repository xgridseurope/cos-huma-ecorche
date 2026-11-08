# COS HUMA Écorché B — v1.5.0 device test site

Independent experimental version (not COS HUMA A, not the live site).

- `index.html` — v1.5.0 phase 1: 3D skeleton/muscles, textbook pp. 25 & 27, quizzes, games, assembly. Self-test: `index.html?selftest=1`.
- `gesture-lab.html` — v1.5.0 phase 2: MediaPipe hand gestures only (open / fist / pinch), left-right calibration,
  guided test, JSON export. It does not load three.js or the 3D model.

Everything is served from this site (three.js, fonts, MediaPipe JS/WASM/model). Camera needs HTTPS.
Licences: three.js MIT (vendor/three/LICENSE); fonts SIL OFL (vendor/fonts); model Écorché / BodyParts3D / Z-Anatomy CC BY-SA;
MediaPipe Apache-2.0.
