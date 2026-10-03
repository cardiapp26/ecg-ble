# ECG BLE

XIAO nRF52840 + AD8232 EKG kaydedicisi için sunucusuz telefon arayüzü.
Android Chrome'da Web Bluetooth ile cihaza doğrudan bağlanır.

**Aç:** https://cardiapp26.github.io/ecg-ble/ (önceki sürüm)

**v2:** https://cardiapp26.github.io/ecg-ble/v2/ (5 dk HRV ölçümü, RR CSV, HTML rapor)

v2 örnekleme hızını 256 Hz kabul eder (XIAO). CrowPanel 250 Hz gönderir; onunla
nabız ve süreler yaklaşık %2.4 sapar.

`index.html` ve `v2/index.html` otomatik üretilir (ecg-recorder projesinde `tools/gen_ble_page.py`), elle düzenleme.

> Eğitim/araştırma amaçlıdır. Tıbbi teşhis için değildir, kalibre edilmemiştir.
