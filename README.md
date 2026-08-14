# Hi, I'm Safdar Hussain

I build end-to-end products in Hyderabad, India — machine learning, computer vision, and full applications — and I publish them with measured results. Everything below runs live in your browser, on your device, and every headline claim in a README is backed by a test you can run.

## Projects

**[WardOS](https://github.com/safdar-hussain1/wardos)** — a hospital management system that runs entirely in the browser. Real SQLite (WASM), 32 beds, six months of history, an event-sourced audit log, and a time machine that replays the hospital to any moment. Zero server; nothing leaves your device. Double-booking a bed is impossible by schema, money is integer paise end to end, and 318 tests mutation-test every headline claim.
→ [Use it live](https://safdar-hussain1.github.io/wardos/)

**[Nightingale](https://github.com/safdar-hussain1/nightingale)** — disease risk prediction done honestly: six calibrated clinical models (heart disease, diabetes, chronic kidney disease, liver disease, breast and cervical cancer) trained on 257,010 records. Cross-fitted calibration, conformal uncertainty, external validation across four hospitals, and an Ed25519-signed provenance chain. All six models run live in the browser, pinned to the Python originals at 1e-15.
→ [Open the dashboard](https://safdar-hussain1.github.io/nightingale/)

**[TrafficLens](https://github.com/safdar-hussain1/trafficlens)** — traffic analytics from any camera: vehicle counting, tracking, and calibrated speed estimation with YOLO11 + ByteTrack. Counting is segment-intersection geometry, so it can't miss a fast crossing — identical counts at 30 fps and 10 fps. Speeds come from a homography surveyed off the road markings, validated to 0% error on synthetic ground truth. Over-limit vehicles get photographed automatically.
→ [See the control room](https://safdar-hussain1.github.io/trafficlens/)

**[Red Light, Green Light](https://github.com/safdar-hussain1/red-light-green-light-cv)** — a computer-vision referee for the Squid Game challenge. Point a camera at the players: it finds everyone, tracks them, and calls out whoever moves on red light. Playable in your browser with your webcam, everything on-device, and the same scoring kernel runs bit-for-bit in Python — the live page re-verifies its own fixtures.
→ [Play it](https://safdar-hussain1.github.io/red-light-green-light-cv/)

**[Virtual Makeup Studio](https://github.com/safdar-hussain1/virtual-makeup)** — real-time makeup try-on: 468-point face tracking applies lipstick, eyeshadow, eyeliner and blush that follow you on camera. Pigment goes on in CIELAB so skin texture survives, and the engine is benchmarked against four deliberately broken baselines on 25 real portraits.
→ [Try it on your camera](https://safdar-hussain1.github.io/virtual-makeup/)

**[HomeCast](https://github.com/safdar-hussain1/homecast)** — property price prediction for Indian cities. A gradient-boosted valuation model with leak-free cross-validation, benchmarked against the rule of thumb agents actually use, running live in the page — trees exported to JSON and walked in JavaScript, pinned to Python at 1e-9.
→ [Price a property](https://safdar-hussain1.github.io/homecast/)

**[Health Haven](https://github.com/safdar-hussain1/health-haven)** — a hospital management system in Java 21: layered domain model, SQLite, bcrypt auth, and three interfaces (Swing desktop, CLI, JSON API) in one jar. It ships with an executable audit of my 2024 college version's billing bug — a 91% revenue shortfall, reproduced and fixed: `java -jar health-haven.jar audit`.
→ [Read the audit](https://safdar-hussain1.github.io/health-haven/)

## How I work

The pattern across all of these: measure, don't claim. Benchmarks against naive baselines, mutation tests that break a mechanism and check a test fails, honest negative results published next to the wins, and browser demos that run the real model — not a video of it.

**Stack:** Python (scikit-learn, XGBoost, OpenCV, YOLO, MediaPipe, pytest) · TypeScript/JavaScript (React, sql.js, Vitest) · Java 21 (Maven, JUnit) · SQLite

## Find me

- LinkedIn: [Safdar Hussain](https://www.linkedin.com/in/safdar-hussain-a8a61b248)
- GitHub: you're here — [github.com/safdar-hussain1](https://github.com/safdar-hussain1)
