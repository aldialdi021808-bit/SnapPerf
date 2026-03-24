### SnapPerf v1.5.5 (Stable)

### Added
- Notifikasi status bar aktif saat tweak diterapkan
- Boot notification otomatis setelah reboot
- Binary `snapperf-tweaks` (ARM64 compiled) menggantikan `apply-tweaks.sh`
- Boot timeout guard (max ~4 menit) agar tidak hang di `boot_completed`

### Fixed
- Notifikasi Shell tidak aktif / tidak muncul di status bar
- Bootloop di Poco F7 & Poco F7 Pro (SM8635 / SM8650)
- `scaling_max_freq` tidak lagi menulis nilai `9999999` yang menyebabkan kernel panic
- GPU clock restore kini baca dari hardware (`gpu_max_clock`), bukan nilai hardcode
- Deteksi Poco F7 diperluas: SoC `crow` (SM8635), codename `leite` / `thunder`
- Block device I/O tuning kini auto-detect `sda` / `sdb` / `mmcblk0`
- `sched_boost` dilewati jika node tidak tersedia di kernel tertentu
  
### SnapPerf v1.5.4 (Stable)
### Added
- Mode Refresh Rate with (Auto/60/90/120/144)
- Mode Touch Boost

### Fixed 
- Delete GPU Governor 
- Bootloop in Poco F7 Pro
- Bug Modules not Showing in APatch
