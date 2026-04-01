# PhonixUI v1.0 PhonixUI Framework ✦

PhonixUI is a premium, zero-dependency, mobile-first CSS framework designed to give your web applications a stunning, glassmorphic, and highly animated aesthetic right out of the box.

It scales with a Bootstrap-level architecture (familiar class names) while leveraging cutting-edge OKLCH color science, fluid typography (`clamp()`), and GPU-accelerated hover FX.

## ⚡ Features

* **Zero Dependencies:** No npm, no PostCSS, no purge setup. Just link a single `phonixUI.min.css` file.
* **OKLCH Color Engine:** Full-theme switching by changing a single CSS variable (`--ph-base-hue`). Perceptually uniform colors across P3 wide-gamut displays.
* **Glass Aesthetic:** Native utility classes for frosted glass blurs, 3D card lifts, and glowing button shadows.
* **Fluid Typography:** Typography scales infinitely from mobile devices to 4K monitors natively using CSS `clamp()`.
* **Accessible by Default:** Focus-visible keyboard rings, ARIA compatibility, skip links, and total `prefers-reduced-motion` compliance built right in.
* **Familiar API:** Uses standard class conventions (`.btn`, `.card`, `.d-flex`) so your learning curve is completely flat.

## 🚀 Quick Start

### 1. Link the Stylesheet
Download the `phonixUI.min.css` file from this repository and drop it directly into your HTML `<head>` tag.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Phonix App</title>
  <link rel="stylesheet" href="./phonixUI.min.css">
</head>
<body class="theme-blue">
  <div class="container p-y-64">
    <h1 class="text-4xl font-bold text-primary animate-fade-up">Hello, Phonix!</h1>
    <button class="btn btn-primary ph-btn-glow m-t-24">Get Started</button>
  </div>
</body>
</html>