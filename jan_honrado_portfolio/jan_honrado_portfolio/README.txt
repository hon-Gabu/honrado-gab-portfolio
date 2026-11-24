# Jan Gabriel Honrado — Personal Portfolio

## Run locally
1. Extract the ZIP file.
2. Open the `jan_honrado_portfolio` folder in VS Code.
3. Add your profile photo to the `assets` folder and name it `profile.jpg`.
4. Open `index.html` in your browser, or use the VS Code Live Server extension.

## Add your profile photo
The hero currently shows a designed placeholder. To use your photo:
- Put your image at `assets/profile.jpg`.
- In `index.html`, find the `<div class="photo-placeholder"> ... </div>` block.
- Replace that block with:
  `<img class="profile-photo" src="assets/profile.jpg" alt="Jan Gabriel Honrado">`
- Add this to `style.css`:
  `.profile-photo { width:100%; height:calc(100% - 42px); margin:13px 0; object-fit:cover; object-position:center; }`

## Personalize
- Update project descriptions as your projects progress.
- Add your GitHub URL when available.
- Add a LinkedIn URL to the contact section if you want it displayed.
- The email button already opens a message to your provided email address.

This is a static HTML/CSS/JavaScript site; no build tools or installation are required.
