# Hi, I'm Safdar Hussain

I'm a computer science graduate. I build end-to-end products — machine learning, computer vision and full applications — and I publish them with measured results. Every project below has a live page you can open, most of them running entirely on your own device, and every headline claim in a README is backed by a test you can run.

## Projects

**[WardOS](https://github.com/safdar-hussain1/wardos)** — a hospital management system that runs entirely in the browser. Real SQLite (WASM), 32 beds, six months of history, an event-sourced audit log, and a time machine that replays the hospital to any moment. Zero server; nothing leaves your device. Double-booking a bed is impossible by schema, money is integer paise end to end, and 343 tests mutation-test every headline claim.
→ [Use it live](https://safdar-hussain1.github.io/wardos/)

**[Nightingale](https://github.com/safdar-hussain1/nightingale)** — disease risk prediction done honestly: six calibrated clinical models (heart disease, diabetes, chronic kidney disease, liver disease, breast and cervical cancer) trained on 257,010 records. Cross-fitted calibration, conformal uncertainty, external validation across four hospitals, and an Ed25519-signed provenance chain. All six models run live in the browser, matching the Python originals to within 1e-15.
→ [Open the dashboard](https://safdar-hussain1.github.io/nightingale/)

**[TrafficLens](https://github.com/safdar-hussain1/trafficlens)** — traffic counting from one camera. Draw a gate and it counts what crosses it, by class and by direction, and estimates speed only where the camera is calibrated — otherwise it returns no speed rather than a number it can't back. The same engine runs as a Python package and in the browser, where YOLO11 runs on your own machine through ONNX Runtime Web. On hand-labelled footage the gate rule scores F1 0.91–0.94 whichever tracker feeds it, while the common band and per-frame rules collapse below 0.12: the counting rule matters more than the tracker.
→ [Count some traffic](https://safdar-hussain1.github.io/trafficlens/)

**[Red Light, Green Light](https://github.com/safdar-hussain1/red-light-green-light-cv)** — a computer-vision referee for the Squid Game challenge. Point a camera at the players: it finds everyone, tracks them, and calls out whoever moves on red light. Playable in your browser with your webcam, everything on-device, and the same scoring kernel runs bit-for-bit in Python — the live page re-verifies its own fixtures.
→ [Play it](https://safdar-hussain1.github.io/red-light-green-light-cv/)

**[Carmine](https://github.com/safdar-hussain1/carmine)** — virtual makeup that leaves skin looking like skin. It tints lips, eyes, brows and cheeks in CIELAB instead of painting over them, so texture, highlights and shadow survive. A Python engine handles photos and video; a WebGL2 mirror does the same live on your camera at about 37 fps on an M1 Pro, and the two implementations are checked against each other on every build. Benchmarked against four common ways AR makeup filters break, on 26 real portraits.
→ [Try the live mirror](https://safdar-hussain1.github.io/carmine/)

**[HomeCast](https://github.com/safdar-hussain1/homecast)** — property price prediction for Indian cities. A gradient-boosted valuation model with leak-free cross-validation, benchmarked against the rule of thumb agents actually use, running live in the page — trees exported to JSON and walked in JavaScript, pinned to Python at 1e-9.
→ [Price a property](https://safdar-hussain1.github.io/homecast/)

**[Health Haven](https://github.com/safdar-hussain1/health-haven)** — a hospital management system in Java 21: layered domain model, SQLite, bcrypt auth, and three interfaces (Swing desktop, CLI, JSON API) in one jar. It ships with an executable audit of a billing bug that caused a 91% revenue shortfall — reproduced and fixed: `java -jar health-haven.jar audit`.
→ [Read the audit](https://safdar-hussain1.github.io/health-haven/)

## How I work

The pattern across all of these: measure, don't claim. Benchmarks against naive baselines, mutation tests that break a mechanism and check a test fails, honest negative results published next to the wins, and browser demos that run the real model — not a video of it.

**Stack:** Python (scikit-learn, XGBoost, OpenCV, YOLO, MediaPipe, pytest) · TypeScript/JavaScript (React, sql.js, WebGL2, ONNX Runtime Web, Vitest) · Java 21 (Maven, JUnit) · SQLite · GitHub Actions

## Find me

- LinkedIn: [Safdar Hussain](https://www.linkedin.com/in/safdar-hussain-a8a61b248)
- GitHub: you're here — [github.com/safdar-hussain1](https://github.com/safdar-hussain1)
