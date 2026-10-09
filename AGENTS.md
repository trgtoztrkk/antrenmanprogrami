# AGENTS.md

## Mimari
Derleme adımı olmayan statik site. `netlify.toml` yayın klasörünü proje kökü (`.`) olarak ayarlar.

## Dosyalar
- `index.html` — tek sayfa; kullanıcının içeriği burada. Stiller satır içi `<style>` bloğunda.
- `manifest.webmanifest` — ana ekrana eklendiğinde uygulama gibi (standalone) açılması için.
- `netlify.toml` — yayın ayarı.

## Kurallar
- Framework veya build aracı eklemeyin; sayfa basit kalmalı.
- iOS meta etiketlerini (`apple-mobile-web-app-*`, `viewport-fit=cover`) ve safe-area dolgularını koruyun.
- Kullanıcı Türkçe konuşuyor; metinler Türkçe.
