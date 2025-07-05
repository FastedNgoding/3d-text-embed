# 3D Text Embed

Hi there! 👋  
This is a lightweight, embeddable 3D text generator built with [Three.js](https://threejs.org/). It’s great for showcasing names, titles, or any short message in style — with full control via URL parameters.

---

## ✨ Features

- Dynamic 3D text with bevel and lighting
- Drag/touch to rotate (limited angle)
- Optional animations (idle, rotate, bounce)
- Custom colors (hex or named)
- Transparent background support
- Easy to embed anywhere via iframe

---

## 🔧 Usage

Include the HTML on your page or serve it standalone, then control behavior using URL parameters.

### 🔹 Parameters

| Name         | Description                              | Example                          |
|--------------|------------------------------------------|----------------------------------|
| `text`       | The 3D text you want to display           | `?text=Hello+World`              |
| `color`      | Color name or hex (no `#`)                | `?color=red`, `?color=11eee7`    |
| `animation`  | Animation type: `idle`, `rotate`, `bounce`, `none` | `?animation=rotate`     |
| `transparent`| Transparent background (`true/false`)     | `?transparent=true`              |

---

### 💡 Embed Example

```html
<iframe 
  src="https://fastedngoding.github.io/3d-text-embed?text=Welcome&color=white&animation=idle&transparent=true" 
  style="width:100%; height:300px; border:none;" 
  allowfullscreen>
</iframe>
```

---

## ⚠️ Notes

- If you use hex color, avoid the `#` symbol or encode it: `%23ffaa00`
- If no params are provided, it defaults to: `text=Nazri`, `color=#00aaff`, `animation=idle`

---

## 🙏 Acknowledgements

Thanks to:
- God 🙏 — for life and creativity  
- Myself — for putting in the hours  
- ChatGPT — for debugging & guidance  
- The Three.js team — for the incredible engine  
- Everyone who uses and shares this — you rock!  
