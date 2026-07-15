# Neo Glass — Seelen UI Teması

Dock, araç çubuğu ve tüm popup/flyout panelleri için sıfırdan yazılmış **neo-minimalist glassmorphism** teması. "(Neredeyse) Sıvı Cam DockBar" (dock'taki sıvı-cam/blur/parıltı dili) ile "Onyx Bubbles Light & Dark (Adaptive)" (araç çubuğundaki yumuşak, açık/koyu moda uyumlu bubble öğeler) temalarından ilham alınarak inşa edildi.

Seelen UI'nin güncel `--slu-std-*` tasarım token'larını kullanır — Windows vurgu renginize ve açık/koyu sistem temanıza otomatik uyum sağlar.

![Masaüstü genel görünüm](media/D%C3%BCz%20masa%C3%BCst%C3%BC%20medyalar%C4%B1/foto%C4%9Fraf/Screenshot%202026-07-15%20112438.png)

## Öne çıkanlar

- **Segmented toolbar** — araç çubuğu tek parça bir bar yerine sol/orta/sağ olmak üzere bağımsız yüzen cam parçalara ayrılır (profil/uygulamalar solda, sistem tepsisi sağda)
- **Sıvı cam dock** — bulanıklık, parıltı ve kenar yansıması ayarlanabilir yüzen dock
- **Okunaklı popup'lar** — hızlı ayarlar, medya kontrolü, bildirimler, bağlam menüleri dahil 17 farklı widget'ta tutarlı cam efekti; arka planda ne olursa olsun (karmaşık görsel, yoğun metin) metin okunurluğu korunur
- **6 canlı ayarlanabilir değişken** — bulanıklık, opaklık, köşe yuvarlaklığı ve kenar belirginliğini uygulamayı yeniden başlatmadan Seelen UI ayarları içinden değiştirebilirsiniz

## Ekran görüntüleri

### Widget'lar

| Medya paneli | Wi-Fi paneli |
|---|---|
| ![Medya paneli](media/widget%20medyalar%C4%B1/Screenshot%202026-07-15%20141016.png) | ![Wi-Fi paneli](media/widget%20medyalar%C4%B1/Screenshot%202026-07-15%20141053.png) |

### Canlı önizlemeler

<p>
  <img src="media/D%C3%BCz%20masa%C3%BCst%C3%BC%20medyalar%C4%B1/gif/Recording%202026-07-15%20134821.gif" width="49%" />
  <img src="media/D%C3%BCz%20masa%C3%BCst%C3%BC%20medyalar%C4%B1/gif/Recording%202026-07-15%20135005.gif" width="49%" />
</p>
<p>
  <img src="media/D%C3%BCz%20masa%C3%BCst%C3%BC%20medyalar%C4%B1/gif/Recording%202026-07-15%20135145.gif" width="49%" />
  <img src="media/D%C3%BCz%20masa%C3%BCst%C3%BC%20medyalar%C4%B1/gif/Recording%202026-07-15%20135246.gif" width="49%" />
</p>
<p>
  <img src="media/D%C3%BCz%20masa%C3%BCst%C3%BC%20medyalar%C4%B1/gif/Recording%202026-07-15%20135337.gif" width="49%" />
  <img src="media/D%C3%BCz%20masa%C3%BCst%C3%BC%20medyalar%C4%B1/gif/Recording%202026-07-15%20135715.gif" width="49%" />
</p>

## Kurulum

1. [`neo-glass.yml`](neo-glass.yml) dosyasını indirin.
2. Şu klasöre kopyalayın:
   ```
   %APPDATA%\com.seelen.seelen-ui\themes\
   ```
3. Seelen UI'yi açın → **Ayarlar → Kaynaklar → Temalar**'a gidin, **Neo Glass**'ı bulup etkinleştirin.
4. Seelen UI'yi tamamen kapatıp (sistem tepsisinden çıkış) tekrar açın.

## Özelleştirme

Etkinleştirdikten sonra tema ayarları sayfasından şu değişkenleri canlı olarak ayarlayabilirsiniz:

| Değişken | Ne işe yarar | Varsayılan |
|---|---|---|
| `--neo-glass-blur` | Dock ve araç çubuğunun arka plan bulanıklığı | 22px |
| `--neo-glass-opacity` | Dock/araç çubuğu cam opaklığı | %55 |
| `--neo-glass-radius` | Köşe yuvarlaklığı | 20px |
| `--neo-glass-border-opacity` | Kenar çizgisi belirginliği | %16 |
| `--neo-glass-popover-blur` | Popup panellerinin bulanıklığı | 46px |
| `--neo-glass-popover-opacity` | Popup panellerinin opaklığı (okunurluk için yüksek tutulur) | %90 |

## Uyumluluk

- Seelen UI v2.7.x
- Test edilen widget'lar: `weg`, `fancy-toolbar`, `tooltip`, `context-menu`, `notifications`, `quick-settings`, `power-menu`, `bluetooth-popup`, `network-popup`, `calendar-popup`, `apps-menu`, `user-menu`, `system-tray`, `workspaces-viewer`, `keyboard-selector`, `flyouts`, `media-popup`

## Teşekkür

İlham alınan temalar: **(Neredeyse) Sıvı Cam DockBar** (@silva2307) ve **Onyx Bubbles Light & Dark (Adaptive)** (@nevermore).
