# Logo Folder

Place your Reintal GM logo file here.

## Required File:
- **Filename:** `reintal-logo.png` (or `reintal-logo.svg`)
- **Format:** PNG with transparent background (recommended) or SVG
- **Size:** 200-300px width
- **Max file size:** 100KB

## How to Add:
1. Save your logo file as `reintal-logo.png`
2. Copy it to this folder
3. The website will automatically display it in the header

## File Path:
```
C:\Users\elchi\.gemini\antigravity\Reintal_Website\public\images\logo\reintal-logo.png
```

## After Adding:
Update the image path in:
- `index-standalone.html` (line ~407)
- `src/components/Header.jsx` (line 11)

Change from:
```html
src="/path/to/your/logo.png"
```

To:
```html
src="/images/logo/reintal-logo.png"
```
