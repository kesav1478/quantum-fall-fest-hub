# Quantum Fall Fest Hub

Build a React + Vite web app for "Qiskit Fall Fest 2026," a 3-day national quantum computing event (Sept 5–7, 2026) hosted by our college. This is a large, production-quality event site — build it clean and structured, not a quick demo.

Design direction: editorial, futuristic, quantum, playful — NOT a typical conference template. Huge typography, asymmetric layouts, thin borders, editorial section numbering (e.g. "01 / THE EVENT"), generous whitespace, controlled color accents rather than filling everything with cards.

Colors: black (#0A0A0A) as the primary background, off-white (#F5F3F0) as the secondary background/text color, pink (#FF5FA2) as the main accent, and a Qiskit-inspired purple as a secondary accent. Use a bold display font for large headlines and a clean readable font for body text.

Set up React Router with these routes (build only the navigation shell + placeholder content in each for now — do not build full page content yet):

/  /register  /hackathon  /workshops  /day-1  /day-2  /day-3  /certificates  /sponsors  /faq  /contact  /privacy  /code-of-conduct  and a 404 fallback.

Build a shared Navbar: logo/wordmark on the left, links (PROGRAM with a dropdown for DAY 01/02/03, HACKATHON, WORKSHOPS, CERTIFICATES) in the center/right, REGISTER button (pink, filled) and LOGIN on the far right. Navbar background should change once the user scrolls down. On mobile, collapse into a hamburger menu that opens a full-screen overlay.

Build a LOGIN as a floating card/modal (not a separate page): email + password fields when logged out; a "Welcome" message with "My Registration" and "Logout" when logged in. Use local state to fake login for now — no real backend yet.

Build a shared Footer with quick links to every route above, plus a copyright line.

Keep animations minimal and fast in this batch — smooth scroll-based navbar transition and a simple fade for the mobile menu is enough. Save bigger animation work for later.

This project was built with [Lovable](https://lovable.dev).

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/f6c1c132-5db1-4a7f-aa85-a19ab3baa2e9).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
