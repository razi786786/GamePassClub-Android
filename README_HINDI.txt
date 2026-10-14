GAMEPASS CLUB ANDROID SOURCE (₹0 build route)

Yeh Android app ka source project hai. Isme abhi local HTML demo bundled hai:
- Free / VIP / PRO plan screen
- Registration demo form
- Form submit par JSON file download ka browser-style behavior Android WebView me device/browser ke hisaab se test karna hoga.
- Online account/database/payment abhi nahi hain. VIP/PRO payments collect na karein jab tak real backend/payment setup na ho.

MOBILE SE APK BANANE KA FREE TAREEQA (GitHub Actions):
1. Phone browser me github.com par sign in karein ya free account banayein.
2. New repository banayein, naam: GamePassClub-Android.
3. Is ZIP ko extract karne ke baad iske andar ki saari files/folders repository me upload karein (ZIP file ko as-is upload karna kaafi nahi; extracted files upload honi chahiye).
4. Commit changes karein.
5. Repository me Actions tab kholein. Agar workflow prompt aaye to enable karein.
6. "Build GamePass Club APK" workflow choose karke Run workflow dabayein.
7. Build complete hone par workflow run ke neeche Artifacts me GamePassClub-debug-apk download karein.
8. ZIP artifact extract karein; app-debug.apk milega. APK ko apne Android phone par kholkar install karein. Phone security prompt aaye to sirf apne banaye hue APK ke liye installation allow karein.

ZAROORI:
- GitHub Actions ki free usage limits/policies apply hoti hain; isliye ise guaranteed unlimited free service na samjhein.
- Yeh debug APK hai, Play Store release ke liye signed release build aur Play Console ki zarooratein alag hain.
- Abhi data online save nahi hota; registration details local demo workflow ke liye hain.
- Garena/Free Fire se official affiliation nahi hai. Kisi publisher ka logo ya paid game items bina permission sell na karein.
