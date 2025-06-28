# 📄 PDF.js Custom Viewer

This repository provides a customized version of [Mozilla’s PDF.js](https://github.com/mozilla/pdf.js) with modified viewer behavior to **bypass origin checks** and **force loading PDF files from any URL**, including cross-origin sources.

---

## ✨ Features

- ✅ **Bypass Origin Checks** – Allows PDF loading from any domain without CORS errors.
- ✅ **No Modifications to Core Renderer** – Keeps `/pdf.mjs` unchanged for compatibility and stability.
- ✅ **Two Versions Available** – Choose between Alist-compatible (V1) or latest Mozilla version (V2).

---

## 🛠 Modified Files

| File              | Status / Notes                                     |
|-------------------|----------------------------------------------------|
| `/web/viewer.mjs` | ✅ Modified to bypass origin validation             |
| `/build/pdf.mjs`  | 🔒 Unchanged – Maintains original PDF.js behavior  |

---

## 🚀 Usage

### 🔗 Version 1 – Alist-Compatible PDF.js Viewer
> URL:  
```
https://pdf-js.dkly.top/pdf.js/web/viewer.html?file=<your-pdf-url>
```

- Optimized for platforms like **Alist**
- Stable legacy version with origin check bypass

---

### 🔄 Version 2 – Latest Mozilla PDF.js Viewer
> URL:  
```
https://pdf-js.dkly.top/web/viewer.html?file=<your-pdf-url>
```

- Based on the latest [PDF.js](https://github.com/mozilla/pdf.js)
- Modern UI and improved rendering
- Origin check bypass enabled
- [v5.3.31](https://github.com/mozilla/pdf.js/releases/tag/v5.3.31)

---

## 📝 Example

Open a remote PDF:
```
https://pdf-js.dkly.top/web/viewer.html?file=https://example.com/sample.pdf
```

> **Note:** Ensure the `file` URL is properly URL-encoded.

---

## 📂 Deployment Notes

- Hosted on: `https://pdf-js.dkly.top`
- You can self-host this version or integrate it with cloud storage and media managers like Alist.

---

## 📃 License

This project is based on [Mozilla PDF.js](https://github.com/mozilla/pdf.js), licensed under the [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).

---

## 🙋‍♂️ Author

Maintained by [Davon (dkly)](https://www.dkly.top/).  
For questions or integration help, feel free to reach out!
