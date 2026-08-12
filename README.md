# Instead · Privacy Policy

Static Privacy Policy page for the **Instead** Android app (GitHub Pages).

## Live URL (after Pages is enabled)

https://linea12.github.io/instead-privacy/

## Setup

1. Create a new public GitHub repository named `instead-privacy` under `linea12` (empty, no README).
2. From this folder:

```powershell
cd C:\Users\laura\Workspace\instead-privacy
git init
git add .
git commit -m "Add Instead privacy policy for GitHub Pages"
git branch -M main
git remote add origin https://github.com/linea12/instead-privacy.git
git push -u origin main
```

3. On GitHub: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main** / **/ (root)**
   - Save

4. After a minute, open https://linea12.github.io/instead-privacy/

5. Put that URL in:
   - Google Play Console (Privacy Policy)
   - Instead app: `PrivacyPolicyUrl` in `AboutScreen.kt`
