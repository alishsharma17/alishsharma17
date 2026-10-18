<div align="center">

<img src="assets/banner.png" alt="Alish Sharma: software engineer who ships products end to end, from 3D web apps to iOS marketplaces to the network underneath them. CS at Texas A&M, Field Engineer at United Airlines, Founder of Mowvi." width="100%">

<br><br>

<a href="https://www.linkedin.com/in/alish-sharma-357760257/"><img src="https://img.shields.io/badge/LinkedIn-19352A?style=for-the-badge&logo=linkedin&logoColor=C7FF3D" alt="LinkedIn"></a> <a href="mailto:alish1704@tamu.edu"><img src="https://img.shields.io/badge/Email-19352A?style=for-the-badge&logo=gmail&logoColor=C7FF3D" alt="Email"></a> <a href="https://paddockk.alishsharma88.workers.dev"><img src="https://img.shields.io/badge/Live_demo-PADDOCKK-19352A?style=for-the-badge&labelColor=C7FF3D" alt="Live demo: PADDOCKK"></a> <a href="https://pulse.alishsharma88.workers.dev"><img src="https://img.shields.io/badge/Live_demo-Earth//Pulse-19352A?style=for-the-badge&labelColor=C7FF3D" alt="Live demo: Earth//Pulse"></a>

</div>

<br>

I study computer science at **Texas A&M**, keep airline systems running as a **Field Engineer at United Airlines**, and I'm building **Mowvi**, an on-demand lawn care marketplace for iOS.

I like products that work all the way down: the interface, the data model, and the network it runs on. Below are things I've designed, built, tested and shipped myself.

<br>

## ◼ Building now

<img src="assets/mowvi.png" alt="Mowvi: book a vetted local lawn pro in under a minute, with the price upfront. Built with SwiftUI, Supabase and PostgreSQL, and Stripe Connect." width="100%">

**Mowvi** is a two-sided marketplace. Homeowners book lawn care with an upfront price, local pros accept the job, and the platform handles everything in between. It's a native iOS app on a Supabase/PostgreSQL backend, with Stripe Connect for payments.

- **Escrow-style payments.** The card is authorized at booking and captured only after the job is verified complete with photos.
- **Instant payouts.** Stripe Connect pays the pro as soon as the job is done.
- **Discover feed.** People post their yards, follow each other and see which pro did the work, so the app is useful between bookings.

<br>

## ◼ Selected work

### 🏁 PADDOCKK · *The sport, decoded.*

<a href="https://paddockk.alishsharma88.workers.dev"><img src="assets/paddockk.jpg" alt="PADDOCKK homepage: 'The sport. Decoded.' over a 3D outline of the Circuit of the Americas with a live race countdown" width="100%"></a>

<table>
  <tr>
    <td width="50%"><img src="assets/paddockk-live.jpg" alt="Live timing tower with gaps, tyres and pit stops beside a track map"><br><sub><b>Live</b>: the race reconstructed lap by lap</sub></td>
    <td width="50%"><img src="assets/paddockk-lab.jpg" alt="Concept car exploded into labelled parts with a team colour picker"><br><sub><b>Lab</b>: explode a concept car into 13 parts</sub></td>
  </tr>
</table>

An independent Formula 1 platform with **nine modules**: live timing, a strategy model you can share as a link, stats, replays of any race since 1996, all 23 circuits in 3D, a car you can take apart, interactive lessons, predictions, and a widget workspace you build yourself. Every number shows where its data came from.

`Next.js 16` `React 19` `TypeScript` `Three.js / R3F` `Supabase` `Cloudflare Workers` `Vitest` `Playwright`

**[▶ Live site](https://paddockk.alishsharma88.workers.dev)** · [Source](https://github.com/alishsharma17/apex)

<br>

### 🌍 EARTH//PULSE · *A living planet you can explore.*

<a href="https://pulse.alishsharma88.workers.dev"><img src="assets/pulse.jpg" alt="Earth//Pulse: an illustrated 3D globe with live weather, earthquake and storm markers, a local forecast card and a minimap" width="100%"></a>

Spin an illustrated 3D Earth, then dive from space to street-level maps without a seam. The globe and map share one camera model, and the handoff between them measures **0 px** of drift, even across the antimeridian. It has live earthquakes, storms, fires and volcanoes, weather, dated satellite imagery, guided stories and a Pomodoro timer, with a source and timestamp on every data point.

`Next.js` `React Three Fiber` `MapLibre GL` `NASA GIBS / EONET` `USGS` `Open-Meteo` `Cloudflare Workers`

**[▶ Live site](https://pulse.alishsharma88.workers.dev)** · [Source](https://github.com/alishsharma17/pulse)

<br>

### 🤖 KINETIC · *Movement becomes instruction.*

<img src="assets/kinetic-studio.jpg" alt="Kinetic Studio: a humanoid robot arm with a five-finger hand on a physics bench, with control panels and live joint telemetry" width="100%">

<table>
  <tr>
    <td width="50%"><img src="assets/kinetic-two-hands.jpg" alt="Two-hand tracking mode"><br><sub><b>Two hands</b>: whole-hand mirroring from a webcam</sub></td>
    <td width="50%"><img src="assets/kinetic-games.jpg" alt="Games built on top of hand tracking"><br><sub><b>Games</b>: five mini-games you play with your hands</sub></td>
  </tr>
</table>

A robotics lab in the browser. Your webcam watches your hand, and **Kiki**, a humanoid robot arm, copies it: palm, wrist twist, and every finger joint. It uses closed-form inverse kinematics, MediaPipe running in a Web Worker, One Euro smoothing, and Rapier physics so you can pick things up. You can record demonstrations at 30 Hz and export them as JSON for training data. Everything runs locally, with no backend.

`React` `TypeScript` `Three.js` `MediaPipe` `Rapier` `Web Workers` `IndexedDB` `Vite` `Playwright`

[Source](https://github.com/alishsharma17/kinetic)

<br>

### ✦ Portfolio · *An interactive poster with a codebase under its surface.*

<table>
  <tr>
    <td width="50%"><img src="assets/portfolio.jpg" alt="Portfolio homepage: giant ALISH SHARMA type over a topographic contour field, with a liquid-glass cursor lens"><br><sub><b>Home</b>: move the cursor and the lens reveals hidden code</sub></td>
    <td width="50%"><img src="assets/portfolio-projects.jpg" alt="Portfolio projects index with oversized MOWVI and THIS PORTFOLIO rows"><br><sub><b>Projects</b>: an editorial index with hover previews</sub></td>
  </tr>
</table>

My personal site, built as an interactive editorial piece. A topographic contour field drawn with **marching squares** reacts to your cursor, and a 48px **liquid-glass lens** follows the pointer to reveal a hidden layer of code. It has a cinematic preloader, panel-wipe page transitions, pinned scroll sections and horizontal galleries, plus fallbacks for reduced motion and touch. All content lives in typed data files, so updating it never means touching animation code.

`Next.js 16` `TypeScript` `GSAP + ScrollTrigger` `Lenis` `Canvas` `Tailwind CSS v4`

[Source](https://github.com/alishsharma17/alish-portfolio)

<br>

### 🧠 BRAINROT.EXE · *Your last two brain cells are fighting for third place.*

<img src="assets/brainrot.png" alt="Brainrot.exe: 34 3D pets, 7 themed zones, 66 achievements, 42 Luau unit tests" width="100%">

An intentionally absurd, surprisingly deep **Roblox simulator** with 18 generators, 34 code-built 3D pets, 23 random events, seven zones, a boss fight against *The Algorithm*, and a 24-node prestige skill tree. Underneath is serious engineering: a server-authoritative engine, DataStores with session locking, idempotent purchase receipts, and 42 unit tests type-checked against the Roblox API.

`Luau` `Rojo` `DataStoreService` `MarketplaceService` `luau-lsp`

[Source](https://github.com/alishsharma17/brainrot)

<br>

## ◼ Earlier work

| | Project | What it is |
| :-: | --- | --- |
| 🚗 | **MechAI** | AI vehicle diagnostics: upload a photo and get likely issues and troubleshooting steps. React Native + FastAPI. |
| 🏢 | **Enterprise AD & Network Homelab** | Windows Server lab with Active Directory, DNS, DHCP, VLANs, inter-VLAN routing, VMware and Cisco gear. |
| 🔌 | **Network Automation** | Python tools that automate config management, monitoring and admin tasks across enterprise networks. |

<br>

## ◼ Toolbox

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,py,swift,java,cpp,lua&theme=light" alt="TypeScript, JavaScript, Python, Swift, Java, C++, Lua"><br>
  <img src="https://skillicons.dev/icons?i=react,nextjs,threejs,tailwind,vite,nodejs,fastapi&theme=light" alt="React, Next.js, Three.js, Tailwind, Vite, Node.js, FastAPI"><br>
  <img src="https://skillicons.dev/icons?i=postgres,supabase,sqlite,cloudflare,aws,linux,git&theme=light" alt="PostgreSQL, Supabase, SQLite, Cloudflare, AWS, Linux, Git">
</p>

**Also:** React Native & Expo · SwiftUI · MapLibre · MediaPipe · Vitest & Playwright · Cisco routing & switching · Windows Server / Active Directory · VMware

<br>

<div align="center">
<sub>Built, tested and shipped by Alish Sharma · <a href="https://www.linkedin.com/in/alish-sharma-357760257/">LinkedIn</a> · <a href="mailto:alish1704@tamu.edu">alish1704@tamu.edu</a></sub>
</div>
