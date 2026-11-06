# Jose Decena — Digital Calling Card

A clean, professional digital calling card / portfolio site for **Jose Decena**, Managing Director of Ascendant Global.

## Photos you need to add

Place these images inside the `assets` folder:

| File name              | Where it appears                              | Recommended size      |
|------------------------|-----------------------------------------------|-----------------------|
| `self.jpg`             | Small square photo (desktop header)           | 400 × 400 px          |
| `hero.jpg`             | **Large photo** (main banner, especially on phone – matches your red rectangle sketch) | 1200 × 600 px or wider |
| `ambassador.jpg`       | Large photo **above** “Australian Ambassador Relations” | 1000 × 500 px        |
| `immersion.jpg`        | Large photo **above** “Australian Immersion Program”   | 1000 × 500 px        |

The partners image (`partners-000.jpg`) is already included.

## Live on GitHub Pages

1. Create a new public GitHub repository.
2. Upload all files from this folder.
3. Go to **Settings → Pages**.
4. Source: **Deploy from a branch** → branch `main` → folder `/ (root)`.
5. Save. Site will be at `https://<username>.github.io/<repo-name>/`.

## Structure

```
website/
├── index.html
├── styles.css
├── script.js
├── assets/
│   ├── partners-000.jpg   ← already included
│   ├── self.jpg           ← you add
│   ├── hero.jpg           ← you add (large phone photo)
│   ├── ambassador.jpg     ← you add
│   └── immersion.jpg      ← you add
└── README.md
```

## Mobile layout (phone)

On phone the layout follows your sketch:
- Name at the top
- Large full-width photo (the red rectangle area) right below the name
- Then the three tabs and content

Desktop still shows the smaller square photo next to the name plus the large hero banner.
