PABRIK KONTEN SEJARAH - ANDROID APK PROJECT
===========================================

Ini adalah proyek Android Studio untuk membuat APK aplikasi "Pabrik Konten Sejarah".

Fungsi:
- Dipasang sekali di Android.
- URL backend hanya dimasukkan sekali dan disimpan di HP.
- Setelah itu: buka aplikasi -> tempel cerita -> BUAT VIDEO LANGSUNG -> Veo -> hasil video tampil -> download MP4.
- API key TIDAK disimpan di APK/HP. API key tetap berada di backend cloud.

PENTING:
APK membutuhkan backend yang sudah aktif, misalnya backend dari paket:
PabrikKonten_Android_PWA_Veo.zip

CARA BUILD APK:
1. Buka folder proyek ini di Android Studio.
2. Tunggu Gradle Sync selesai.
3. Pilih Build > Build App Bundle(s) / APK(s) > Build APK(s).
4. APK biasanya berada di:
   app/build/outputs/apk/debug/app-debug.apk
5. Kirim APK ke HP lalu instal.

BACKEND:
Setelah aplikasi pertama kali dibuka, masukkan URL backend HTTPS Anda, misalnya:
https://nama-project.vercel.app

CATATAN:
Saya tidak menyertakan API key ke aplikasi demi keamanan.
Google AI Pro konsumen dan Gemini Developer API adalah billing yang berbeda.
