
# ALFA Coin Catcher

Hyper-casual Android game (SurfaceView) built with Kotlin. No ads, no network, no tracking.

## Build (Android Studio)
1. Open Android Studio > **Open** > select this folder.
2. Let Gradle sync (Android Gradle Plugin 8.5.2, Kotlin 2.0.0).
3. `Run` on a device to test.
4. To upload to Google Play, build a **signed Android App Bundle (.aab)**: Build > Build Bundle(s) / APK(s) > Build Bundle(s).

## Store assets included
- `assets/icon_play_512.png` – Play icon 512×512 (32‑bit PNG) (meets Play specs).
- `assets/feature_graphic_1024x500.png` – Feature graphic 1024×500 (24‑bit PNG, no alpha).

## Policy & privacy
- `policy/privacy_policy.html` – simple privacy policy (no data collected).
- No permissions requested; no SDKs for ads/analytics. If you add SDKs, update the privacy policy and Play **Data safety** form accordingly.

## Play Console checklist (summary)
- Developer account (one‑time $25 fee).
- Target API level 35 (Android 15).
- Upload **.aab** bundle (App signing by Google Play is default).
- Fill **Data safety** (declare “No data collected” as long as unchanged).
- Add app content: Target audience & content rating questionnaire.
- Upload store listing assets: icon 512×512, feature graphic 1024×500, screenshots.
- Provide a privacy policy URL (you can host the included HTML on any web host).

> See `store_listing/` for Arabic & English descriptions ready to paste.
