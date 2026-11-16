# Embossed Text Effect — runnable recreation

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-blue?style=for-the-badge&logo=github)](https://mrchandrayee.github.io/embossed-text-effect/)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org) [![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](./LICENSE)

This project recreates the **Embossed Text Effect** screen recording. It presents four neumorphic text treatments on a pale blue-grey surface, with inset preview panels and dark CSS code windows.

## Effects shown in the video

1. **Soft Emboss** — `EMBOSS`
2. **Deep Emboss** — `EMBOSS`
3. **Debossed (Pressed Inward)** — `PRESSED`
4. **Metallic Emboss** — `METAL`

## CSS transcribed from the visible code panels

### Soft Emboss
```css
.emboss-soft {
  text-shadow:
    -1px -1px 2px rgba(255,255,255,.8),
     1px  1px 2px rgba(0,0,0,.2);
}
```

### Deep Emboss
```css
.emboss-deep {
  color: #c5cedd;
  text-shadow:
    -2px -2px 4px rgba(255,255,255,.9),
     2px  2px 4px rgba(0,0,0,.3),
    -1px -1px 0 rgba(255,255,255,.5),
     1px  1px 0 rgba(0,0,0,.2);
}
```

### Debossed
```css
.debossed {
  text-shadow:
     1px  1px 2px rgba(255,255,255,.8),
    -1px -1px 2px rgba(0,0,0,.3);
}
```

### Metallic Emboss
```css
.emboss-metal {
  color: #b0b5c0;
  text-shadow:
    -1px -1px 0 rgba(255,255,255,.7),
     1px  1px 0 rgba(0,0,0,.6),
    -2px -2px 5px rgba(255,255,255,.5),
     2px  2px 5px rgba(0,0,0,.5);
}
```

## Run

1. Extract the ZIP.
2. Open `index.html` in a modern browser.
3. Scroll through the four effects.

No JavaScript, external libraries, build process, or server is required.

## Files

- `index.html` — page structure and all four demonstrations
- `style.css` — neumorphic surfaces, text-shadow effects, code-window styling
- `README.md` — source transcription and usage notes

## Fidelity note

The four effect names, displayed words, and CSS declarations above are transcribed from the readable video panels. The page layout, supporting card styles, and responsive sizing are recreated to provide a complete runnable demo; this is not claimed to be the creator's full original source.

## 👨‍💻 Author

**mrchandrayee** · [GitHub](https://github.com/mrchandrayee)

## 📄 License

[MIT License](./LICENSE)
