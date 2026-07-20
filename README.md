# ydscore-data

YDScore uygulamasının uzaktan güncellenebilir verileri.

## exam-calendar.json

Resmî YDS / e-YDS sınav takvimi. Uygulama her açılışta bu dosyanın Raw
URL'sinden güncel tarihleri çeker (24 saatte bir, cihazda önbellenir).
ÖSYM takvim değişikliğinde yalnızca bu dosyayı düzenlemek yeterlidir.

Biçim:

```json
[{ "id": "yds2-2026", "name": "YDS/2", "date": "2026-11-22" }]
```
