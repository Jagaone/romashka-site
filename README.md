# romashka-site

Static public pages for the Romashka app, served by GitHub Pages from `main`.

| Page | Path | Used for |
|---|---|---|
| Account deletion (RU/EN) | `delete-account/` | Google Play → Data safety → Data deletion URL |

Plain HTML, no build step. Fonts (Onest) and brand colours are copied from the Android app
(`romashka-android/app/src/main/res/font`, `presentation/common/theme`). Screenshots come from the app with
personal data blurred.

Preview locally: `python3 -m http.server 8741` and open http://localhost:8741/delete-account/.
