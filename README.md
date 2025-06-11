# Liquid Glass

An interactive demo of an **iOS 26–style Liquid Glass** effect for the web.  
Tweak inner shadows, tint, frost blur, noise distortion and swap out the background image—all live in your browser.

-   **Please file issues** if you spot any quirks or wish to improve or add more controls!

---

## 🎨 Demo

1. Clone or download this repo.
2. Open `index.html` in **Chrome on macOS** (untested on Safari).
3. Use the control panel to play with the effect.

---

## 🚀 Features

-   **Inner Shadow** — blur, spread & color
-   **Glass Tint** — any RGB tint + opacity
-   **Frost Blur** — control the backdrop-filter blur
-   **Noise Distortion** — tweak SVG noise frequency & strength
-   **Background Image** — paste your own URL for the page backdrop
-   **Responsive** — desktop & mobile layouts

---

## 🛠 Usage

Open `index.html` and use the on-screen sliders and color pickers. All changes are applied via CSS variables and an SVG filter.

---

## 🙏 Inspiration

Inspired by Apple’s upcoming **iOS 26 Liquid Glass** design.  
Thanks to [chakachuk’s CodePen demo](https://codepen.io/chakachuk/pen/QwbaYGO) for the original glass-distortion filter setup.

---

## ⚠️ Browser Support

-   **Tested on:** Chrome on macOS
-   **May not work in:** Safari (backdrop-filter and SVG filter support varies)
