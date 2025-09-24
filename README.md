# Pixel Art Converter

This project is a simple **client-side web app** that converts any uploaded image into a pixel-art style version using a **custom color palette** and a **grid** of any size.

## ✨ Features

* **Upload any image** directly from your computer (no backend required).
* **Choose grid width and height**.
* **Add unlimited custom colors** to your palette using color pickers.
* **Automatic color matching**: each cell is filled with the closest color from your palette (Euclidean RGB distance).
* **Side-by-side view** of the original image and the pixelated version.
* 100% client-side — no data uploaded to servers.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/NikoConn/Pixel-art-converter.git
cd pixel-art-converter
```

### 2. Open the app

Just open `index.html` in your favorite browser. No build process or server required.

---

## 🖱️ How to Use

1. **Upload Image**
   Click **“Upload image”** and select a file from your computer.

2. **Set Grid Size**
   Enter the **Grid width** and **Grid height** (number of cells).

3. **Build Color Palette**
   Click **“Add color”** to add more color pickers and choose your custom palette.

4. **Process Image**
   Click **“Process Image”**.

   * Left canvas: Original image.
   * Right canvas: Pixelated image using your palette.
