# tefekkur-assets

Mihrap uygulamasının indirdiği medya için liste dosyaları.

- `manifests/v1/manifest.json`: ana liste (uygulama sürümü ve paketler).
- `manifests/packages/*.json`: her paketin dosya listesi.
- Büyük dosyalar (paket arşivleri, ses ve görseller, APK) git'te değil, GitHub release'lerinde durur; depo bu yüzden büyümez.
