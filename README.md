🌗 Dual Mode Gallery — Light & Dark Theme
An illustrative landing page built with unDraw illustrations that adapts to Light/Dark mode via a smooth theme toggle and clean, accessible styles.

✨ Features

🌓 Theme toggle (Light/Dark) with smooth transitions
💾 Preference persistence via localStorage
🖼️ Theme-aware illustrations (e.g., *_light.svg / *_dark.svg)
📱 Responsive layout and fluid typography
♿ Accessible defaults: focus styles, contrast tokens, reduced motion support
⚡ Zero dependencies (Font Awesome optional)

🧠 How It Works

The <html> element gets a data-theme="light|dark" attribute.
CSS variables (--bg, --fg, --card, etc.) switch values per theme.
A checkbox toggle updates the theme and saves it in localStorage.
unDraw SVGs swap between _light.svg and _dark.svg versions when the theme changes.

🚀 Live Demo
