---

# Tailwind CSS v3 to v4 Config Converter

A simple, browser-based tool to help migrate your `tailwind.config.js` (or .ts) file from v3 syntax to the new CSS-native v4 syntax.



---

## What It Does 🤔

This tool takes a standard Tailwind CSS v3 configuration object and automatically converts theme extensions and plugins into the new v4 format, which uses CSS rules like `@theme`, `@keyframes`, and `@utility`.

### **Features** ✨

* **Theme Conversion**: Converts `theme.extend` properties like `colors`, `screens`, and `fontFamily` into a `@theme` block.
* **Keyframe Conversion**: Translates `keyframes` objects into native CSS `@keyframes` rules.
* **Animation Conversion**: Converts `animation` utilities into basic `@utility` classes.
* **Plugin Imports**: Detects official `@tailwindcss` plugins and converts them to `@import` statements.
* **Dummy Friendly**: Made by me for people like me.

---

## How to Use 🚀

1.  Just goto the Github page linked here.
2.  Finish!
---

## Why I made this?

Cause i'm too used to the old way and too bored to do it manually ;-;

---

## Disclaimer

This converter is designed for common configurations. For highly complex or customized `tailwind.config.js` files, manual adjustments to the output may be necessary.
