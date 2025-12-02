# Product Page Site
A fully interactive 3D product experience built with Next.js, React Three Fiber, GSAP, and Prismic CMS.
Users can explore a mechanical keyboard in 3D, press keycaps with realistic switch sounds, view product details, and proceed through a checkout flow.

## Features
### 3D Interactive Keyboard
* Built using Three.js + React Three Fiber
* Realistic mechanical switch animations
* Key press + release behavior with pointer events
* Dynamic audio feedback for every switch:
    - Red switches
    - Brown switches
    - Blue switches
    - Black switches

### Smooth Scroll Animations
* GSAP + ScrollTrigger timeline animations
* Parallax hero section
* Sequential animations across slices and sections

### CMS-Driven Content
* Fully integrated with Prismic
* Homepage, product pages, specifications, and slices managed via the Prismic dashboard
* Custom slice types located in /customtypes

### Modern UI / UX
* Built with TailwindCSS
* Responsive layout
* Glass, chrome, and metal-inspired UI styles
* Auto-animated buttons using motion-safe transitions

### Checkout Flow
* Simple fake checkout process using:
    */src/checkout.ts*
* Animated "press" button feedback
* */success* page for order confirmation
Switch Sound System
High-quality key switch sounds located in:
/public/sounds/
Triggered dynamically on pointer events.
Tech Stack
Frontend
Next.js 14+ (App Router)
React
TypeScript
TailwindCSS
3D / Animation
React Three Fiber
@react-three/drei
GSAP + ScrollTrigger
Three.js
CMS
Prismic.io
Custom slices (Homepage, Product, Switch)
Other
Audio-based interactions
Smooth hover/press animations
Custom global styles (globals.css)