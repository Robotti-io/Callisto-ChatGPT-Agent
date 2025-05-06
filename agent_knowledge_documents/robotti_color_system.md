# 🎨 Callisto Poster Color System

Use this file to guide emotionally-aligned poster color theming.  
Each theme controls the poster’s **core accent color**, used across the following elements:

- `<h1>` background
- `<h2>` text
- `<h2>` border-bottom
- `.bottom-highlight` background and inset border
- `<a>` tag color

✅ Quick Tips box **must remain fixed**:  

- Background: `#fffbe6`  
- Border: `#ffbf00`  
- Label color: `#ffbf00`

---

## 🧠 Usage

During HTML poster generation, select one of the following tone palettes.  
Replace all relevant color values in the template using inline styles.  
No external CSS files. No JS required.

---

## 🎭 Emotional Tone Themes

### Calm (default)

- Base: `#2b3d78`
- Border: `#c6d4ec`
- Inset: `#dbe3f1`

### Urgent Clarity

- Base: `#a83232`
- Border: `#e2b1b1`
- Inset: `#f4dcdc`

### Optimism

- Base: `#227c5a`
- Border: `#b0d6c6`
- Inset: `#d4ece2`

### Empathetic Risk

- Base: `#5d3f92`
- Border: `#c5b4e0`
- Inset: `#e7ddf6`

### Unsettling / Ambiguous

- Base: `#505050`
- Border: `#bbbbbb`
- Inset: `#e0e0e0`

---

## 🧩 Color Replacement Targets in Template

Replace these CSS values:

```css
# h1
background: BASE;

# h2
color: BASE;
border-bottom-color: BORDER;

# .bottom-highlight
background-color: BASE;
box-shadow: 0 0 0 2px INSET inset;

# a
color: BASE;

# .quote (optional)
border-left-color: BORDER;
```

---

## 🧠 GPT Output Notes

Your final HTML must:

- Use only the selected palette
- Inline all styles (no `<link>` or `<script>`)
- Match tone to content (you may suggest theme in title ritual step)