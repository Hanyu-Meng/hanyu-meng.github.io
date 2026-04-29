# Hanyu Meng Personal Website

This is the source code for Hanyu Meng's personal academic website, designed for GitHub Pages.

## How to publish

1. Download and unzip this folder.
2. Copy all files into your GitHub repository:

   `https://github.com/Hanyu-Meng/hanyu-meng.github.io`

3. Add your CV as:

   `assets/Hanyu_Meng_CV.pdf`

4. Commit and push the files to the `main` branch.
5. Open:

   `https://hanyu-meng.github.io`

## File structure

```text
.
├── index.html
├── assets
│   ├── css
│   │   └── style.css
│   └── Hanyu_Meng_CV.pdf
└── README.md
```

## Notes

- Replace the placeholder publication list in `index.html` with your final publications.
- To add a personal photo, place it in `assets/profile.jpg` and replace the `profile-placeholder` block in `index.html` with:

```html
<img class="profile-photo" src="assets/profile.jpg" alt="Hanyu Meng">
```

Then add this to `assets/css/style.css`:

```css
.profile-photo {
  width: 168px;
  height: 168px;
  object-fit: cover;
  border-radius: 50%;
  margin-bottom: 28px;
}
```
