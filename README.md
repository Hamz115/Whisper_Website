# TurboDictate Download Website

This folder contains the download website for TurboDictate.

## Files to add before deploying:

1. **TurboDictate_Setup_1.0.0.exe** - Windows installer
   - Build with: `cd API_WHISPER && .\build_installer.bat`
   - Copy from: `API_WHISPER/installer_output/TurboDictate_Setup_1.0.0.exe`

2. **TurboDictate.apk** - Android app
   - Build with: `cd whisper_mobile && flutter build apk --release`
   - Copy from: `whisper_mobile/build/app/outputs/flutter-apk/app-release.apk`
   - Rename to: `TurboDictate.apk`

## Deploying to GitHub Pages:

1. Create a new GitHub repository (e.g., `turbodictate-download`)
2. Copy all files from this folder to the new repo
3. Push to GitHub
4. Go to repo Settings → Pages → Enable GitHub Pages from main branch
5. Your site will be live at: `https://yourusername.github.io/turbodictate-download/`

## File structure:

```
Whisper_Website/
├── index.html              # Main download page
├── privacy-policy.html     # Privacy policy
├── TurboDictate_Setup_1.0.0.exe  # (add this)
├── TurboDictate.apk        # (add this)
└── README.md               # This file
```
