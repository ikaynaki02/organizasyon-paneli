# Organizasyon Paneli - APK Derleme Projesi

Bu klasördeki dosyaları GitHub'a yükleyip "Actions" sekmesinden
APK'nın otomatik olarak bulutta derlenmesini sağlayabilirsiniz.

## Klasör yapısı
- `www/index.html` — Organizasyon paneli uygulamasının kendisi
- `package.json` — Capacitor bağımlılıkları
- `capacitor.config.json` — Uygulama adı ve paket kimliği
- `.github/workflows/build-apk.yml` — GitHub'da otomatik APK derleme talimatı

## Nasıl kullanılır
Sohbetteki adım adım talimata bakın. Özetle:
1. GitHub'da yeni, boş bir repo oluşturun.
2. Bu klasördeki tüm dosya ve klasörleri (gizli `.github` klasörü dahil) o repoya yükleyin.
3. Repo sayfasında "Actions" sekmesine gidin, çalışan işin bitmesini bekleyin.
4. İş bitince sayfanın altındaki "Artifacts" bölümünden
   `organizasyon-paneli-apk` dosyasını indirin — içinde `app-debug.apk` var.
