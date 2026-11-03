# VUDEX Golf Pose Lab (prototype)

Face-on golf swing pose analysis in the browser (MediaPipe Pose, on-device).

- `index.html` — app (sample report, video upload analysis, real-time camera capture)
- `sample.js`, `sample/` — sample swing data (김진현 프로, 최미연 팀장, 남궁석 스윙)
- `pose/` — MediaPipe Pose JS solution assets (Apache-2.0, from npm `@mediapipe/pose`); some binaries renamed to `.wasm`
- Static site, no build step. Not indexed (`robots.txt`, `X-Robots-Tag`).
