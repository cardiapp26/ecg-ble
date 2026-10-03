# ECG BLE

AD8232 EKG kaydedicileri için sunucusuz telefon arayüzü.
Android Chrome'da Web Bluetooth ile cihaza doğrudan bağlanır.

| Cihaz | Sayfa | Not |
|---|---|---|
| XIAO nRF52840 | https://cardiapp26.github.io/ecg-ble/xiao/ | 256 Hz, önceki sürüm |
| CrowPanel 2.8 (ESP32-S3) | https://cardiapp26.github.io/ecg-ble/crowpanel/ | 250 Hz, 5 dk HRV ölçümü, RR CSV, HTML rapor |

Kök adres (https://cardiapp26.github.io/ecg-ble/) eski bağlantılar bozulmasın diye
XIAO sayfasıyla aynı kalır.

Sayfalar ecg-recorder projesindeki `tools/gen_ble_page.py` ile üretilir
(`build_page(256)` / `build_page(250)`), elle düzenleme.

> Eğitim/araştırma amaçlıdır. Tıbbi teşhis için değildir, kalibre edilmemiştir.
