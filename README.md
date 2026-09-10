<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=1e3a5f&height=190&section=header&text=Tahsin%20Sakin&fontSize=46&fontColor=f0e68c&animation=fadeIn&fontAlignY=34&desc=I%20build%20the%20thing.%20Then%20I%20delete%20the%20rest.&descAlignY=62&descSize=15" alt="Tahsin Sakin" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tahsinsakin"><img src="https://img.shields.io/badge/LinkedIn-Tahsin%20Sakin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://tahsinsakin.github.io/belvia/"><img src="https://img.shields.io/badge/BudVia-open%20it-f0e68c?style=for-the-badge&labelColor=1e3a5f" alt="BudVia" /></a>
  <a href="https://github.com/tahsinsakin/belvia"><img src="https://img.shields.io/badge/source-on%20the%20table-06b6d4?style=for-the-badge&labelColor=1e3a5f" alt="Source" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/ISE-Ankara%20Bilim-06b6d4?style=flat-square&labelColor=0c1c14" alt="ISE" />
  <img src="https://img.shields.io/badge/Ankara-still%20here-f59e0b?style=flat-square&labelColor=0c1c14" alt="Ankara" />
  <img src="https://img.shields.io/badge/no%20account-on%20purpose-22c55e?style=flat-square&labelColor=0c1c14" alt="no account" />
</p>

## Selam

Information Systems Engineer. Ankara.

Sistemin nasıl kurulduğunu da görürüm, nereden çatladığını da. Okul onu öğretti. Kafa onu sevdi. Fazlalık duran her şeyi keserim. Hesap istemeyen işe hesap koymam. Sunucu istemeyen işi buluta taşımam. Karmaşık duran şeyi karmaşık bırakmam.

Şu an masada duran şey **BudVia**. Ucuz tatilin dağıttığı beş uygulamayı tek plana çevirdim. Kaynak açık. Plan telefonda. Ben de buradayım.

Kısa versiyon: biletleri sen al. Hatırlamayı ben tutarım.

---

## BudVia — asıl iş

Tatili ucuza kuruyorsun. Güzel. Sonra evin dağılıyor.

Uçak Wizz’de. Otobüs FlixBus’ta. Oda Airbnb’de ya da Booking’de. Şehir içi başka yerde. Akşam masası başka yerde. Her teyit ayrı kutuda. Her PNR ayrı mailde. Bir haftayı beş uygulamaya bölüyorsun. Havalimanına çıkmadan önce o beş parçayı tekrar bir trip haline getirmeye çalışıyorsun.

Asıl yorulan yer bilet almak değil. Biletleri hatırlamak.

BudVia o dağınıklığı tek ekrana alıyor.

Satmıyor. Rezervasyon sitesi değil. Yeni bir Wizz değil. Zaten ödediğin şeyleri bir araya getiriyor. Tıkla: bileti aldığın uygulama açılıyor. Wizz Wizz olarak kalıyor. FlixBus FlixBus olarak kalıyor. BudVia onların üstüne çıkmıyor. Aralarındaki boşluğu kapatıyor.

Karşında trip duruyor. Tüm trip.

- Nerede başlayacak
- Ne zaman başlıyor
- Ne kadar erken çıkmalısın
- Ne zaman orada olmalısın
- Hangi yol
- Çantada ne var
- Sıradaki iş ne

Hesap yok. Sunucu yok. Takip yok. Mail istemiyor. “Üye ol” yok. Plan bu telefonun üzerinde duruyor. Silersen biter.

Bunu bu kadar sade yapmak için yazdım. Çünkü tatil zaten yeterince parçalı.

<p align="center">
  <a href="https://tahsinsakin.github.io/belvia/"><img src="https://img.shields.io/badge/Safari%20%C2%B7%20a%C3%A7%20%C2%B7%20Ana%20Ekrana%20Ekle-f0e68c?style=for-the-badge&labelColor=1e3a5f" alt="Open BudVia" /></a>
</p>

| Ekran | Orada ne var |
|---|---|
| **Trip** | Uçuş kartı. Sıradaki hamle. Bugün ne oluyor. |
| **Schedule** | Tarih + saat. “Sabah bir şey vardı” yok. |
| **Places** | Pin. Yol. Harita zaten telefonda. |
| **Bag** | Ne koydun. Ne unuttun. |
| **Tickets** | Wizz, FlixBus, Airbnb, Booking, Bubi. Tık. O uygulama. |

```mermaid
flowchart LR
  A[Wizz / FlixBus / Airbnb / Booking] -->|zaten aldın| B[BudVia]
  B --> C[saat]
  B --> D[yol]
  B --> E[çanta]
  B -->|tık| A
```

Üç adım:

1. [tahsinsakin.github.io/belvia](https://tahsinsakin.github.io/belvia/) — Safari
2. Paylaş → Ana Ekrana Ekle
3. Örnek tripi yükle ya da kendininkini yaz

Kaynak: [tahsinsakin/belvia](https://github.com/tahsinsakin/belvia)  
App Store metni orada duruyor. Bugün PWA yeter.

---

## Masada ne var

| | |
|---|---|
| Ürün | [BudVia](https://tahsinsakin.github.io/belvia/) |
| Kod | [github.com/tahsinsakin/belvia](https://github.com/tahsinsakin/belvia) |
| Okul | Ankara Bilim Üniversitesi — Information Systems Engineering |
| Şehir | Ankara |
| Stack | TypeScript · Expo · React Native · PWA · local-first |
| Kural | Sunucu yoksa sunucu yok |

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,html,css,react,nodejs,git,github,figma" alt="stack" />
</p>

<p align="center">
  <img height="158" src="https://github-readme-stats.vercel.app/api?username=tahsinsakin&show_icons=true&theme=radical&hide_border=true&bg_color=0c1c14&title_color=f0e68c&icon_color=06b6d4&text_color=e5e7eb" alt="stats" />
  <img height="158" src="https://github-readme-stats.vercel.app/api/top-langs/?username=tahsinsakin&layout=compact&theme=radical&hide_border=true&bg_color=0c1c14&title_color=f0e68c&text_color=e5e7eb" alt="langs" />
</p>

---

## Yazışma

Ciddi konu LinkedIn’de. Şaka da orada durabilir. Bakarız.

<p align="center">
  <a href="https://www.linkedin.com/in/tahsinsakin"><img src="https://img.shields.io/badge/linkedin.com%2Fin%2Ftahsinsakin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

An idiot admires complexity, a genius admires simplicity.  
— Terry A. Davis

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=1e3a5f&height=100&section=footer" alt="" />
</p>
