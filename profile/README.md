# LID Labs

Independent software lab. We build low-level things that run in the browser.

Our work sits at the intersection of media engineering and retro hardware: WebAssembly codecs, cycle-accurate emulation, and the tooling that makes both approachable.

## Projects

### [hevc.js](https://github.com/lid-labs/hevc.js)

HEVC/H.265 playback in browsers without native support. A from-scratch C++17 decoder compiled to WebAssembly, transcoding to H.264 in real time via WebCodecs — with drop-in plugins for dash.js and Shaka Player. Ships as an official HEVC playback sample in dash.js 5.2.1+.

1080p @ 60fps · 236KB WASM · zero dependencies · [hevcjs.dev](https://www.hevcjs.dev/)

### Sprixe

A CPS1 arcade studio in the browser. Play 30+ Capcom classics, then open the studio tools: inspect hardware layers in a 3D exploded view, isolate YM2151/OKI audio channels in a piano roll, capture sprites to Aseprite and write modified tiles back to ROM. TypeScript + WebGL2 + WASM.

Source is currently private — [try the live studio](https://arcade-ts.vercel.app).

## How we work

Small team, deep dives. We pick problems where the usual answer is "you can't do that in a browser" and ship the counterexample. Most of what we learn ends up either as open source or as a write-up.

---

Related: [@oberplayer](https://github.com/oberplayer) — our video player product.
