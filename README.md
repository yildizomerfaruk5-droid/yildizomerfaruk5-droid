### Ömer Faruk Yıldız

Computer Engineering student at Erciyes University (2023 to 2028), based in Kayseri, Türkiye.
I build systems where software meets the physical world: an irrigation platform running on real farmland, a satellite pipeline that follows crop growth parcel by parcel, an off-grid sensor network, and offline desktop and mobile apps that keep data on the device.

Every number below comes from my portfolio, where each project page says what was measured and what was not.

**[omerfarukyildiz.vercel.app](https://omerfarukyildiz.vercel.app)** · [LinkedIn](https://www.linkedin.com/in/%C3%B6merfarukyildiz5) · [CV (PDF)](https://omerfarukyildiz.vercel.app/omer-faruk-yildiz-cv-en.pdf)

---

#### Running in production

| Project | What it does | Measured |
|---|---|---|
| [Irrigation Tracking](https://sulama-takip.vercel.app) | Plans, runs and reports irrigation on a working farm. Line transitions run inside PostgreSQL (pg_cron), access is enforced with Row Level Security across four roles. | ~246 decares, ~1,500 GPS-mapped sprinklers, 18 tables, ~16,900 lines |
| [Tarla İzleme](https://tarla-izleme.vercel.app) | Sentinel-2, Sentinel-1 radar, Landsat thermal and weather data turned into per-parcel time series. Checks for new scenes 5 times a day, no API call at view time. | 3 regions, 34 parcels, 8,291 lines of Python |
| [Repo Tarama](https://repo-tarama.vercel.app/?ref=github) | Scores every GitHub repository above 1,000 stars for code quality and maintenance, rule-based, no language model. Refreshed weekly. | 65,677 repositories in the first full scan |

#### Desktop and mobile

| Project | What it does | Measured |
|---|---|---|
| **Okur** | Offline lecture search: GPU transcription, slide-change detection with OCR, scanned PDFs to text, MCP server for Claude Code. | 23.1 hours transcribed at 36.7× real time, 61 tests |
| **Fotoupscale** | 2× and 4× AI upscaling of 200 MP photos on a 6 GB laptop GPU, tiled and resumable, never held in memory. | 200 MP 4× in 869 s at 6.32 GB peak |
| **YerelGaleri** | Offline photo timeline for 100,000+ photos by EXIF date. The spec said exiftool batch mode would win; measured, Pillow was ~10× faster. | Benchmarked on a 150,000-row index |
| **PhotoSense** | On-device photo analysis: Flutter UI over a C++ engine via dart:ffi, one codebase for Windows and Android. | Face detection 100 to 140 ms per photo |
| **Watch face** | Wear OS Watch Face Format dial with a 7-tool Python asset pipeline, running on a Galaxy Watch 4 Classic. | 1.1 MB APK, v1.5.1 |
| **26 Flutter apps** | Small offline apps, each built to test one engineering claim. | 1,393 tests passing, 15 declare no permissions |

#### Hardware

| Project | What it does | Measured |
|---|---|---|
| **MikroKlima-DSS** | Solar-powered ESP32 sensor nodes over ESP-NOW, checking regional forecasts against the field's own microclimate. | 968 packets, 0 lost, 16.8 h autonomous uptime |
| **Bio-Thermal AM Beacon** | Battery-free emergency transmitter powered by body heat (TEG, LTC3108, Colpitts oscillator). | Design stage, no prototype yet |

---

#### Toolkit

**Languages:** Python, JavaScript, TypeScript, C / C++, Dart, Kotlin, SQL
**Web and data:** PostgreSQL, Supabase, Row Level Security, pg_cron, SQLite, Next.js, Vite, Leaflet
**Native:** Flutter, dart:ffi, CMake, Android NDK, Wear OS
**Embedded:** ESP32, ESP-NOW, Arduino framework, sensor calibration, power budgeting

#### Also

- Instructor at T3 Foundation Deneyap Technology Workshops: energy technologies, aviation and space, Flutter
- TEKNOFEST Tourism Technologies Competition finalist, university level (2024)
- Turkish (native), English (B2)

<sub>Most repositories are private. Source and project reports are available on request.</sub>
