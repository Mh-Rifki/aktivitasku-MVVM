# Aktivitasku - MVVM

Aplikasi Counter Aktivitas Harian untuk UTS Pemrograman perangkat Mobile.
Dibuat menggunakan Flutter dengan arsitektur MVVM.

## Fitur
- Tambah, Edit, Hapus Aktivitas
- Counter Tambah / Kurang (tidak bisa < 0)
- Target Harian + Progress Bar
- Notifikasi "Target Hari Ini Tercapai!"
- Reset Counter dengan Konfirmasi
- Hapus dengan Konfirmasi (AlertDialog)
- SnackBar untuk setiap aksi

## Arsitektur MVVM
- **Model:** `activity_model.dart` - Struktur data
- **Data:** `activity_data.dart` - Penyimpanan List
- **Repository:** `activity_repository.dart` - Pengatur akses Data
- **ViewModel:** `activity_viewmodel.dart` - Logika + ChangeNotifier
- **View:** `home_view.dart`, `activity_form_view.dart`, `activity_detail_view.dart`

## Cara Menjalankan
```bash
flutter pub get
flutter run
