# Exile-UI: Türkçe Dil Paketi

![PoE Version](https://img.shields.io/badge/PoE-3.28+-blue) ![Project Status](https://img.shields.io/badge/Durum-Aktif/Beta-green) ![License](https://img.shields.io/badge/Lisans-MIT-orange)

## Kendi başına bir program değildir, Exile-UI uygulamasına ek geliştirilmektedir.

**Exile-UI Türkçe**, Path of Exile oyuncularının (özellikle Act aşamasında zorlanan ve dil bariyerine takılan yeni oyuncuların) aracı en verimli şekilde kullanabilmesi için geliştirilmiş, Exile-UI uygulamasına ek bir yerelleştirme eklentisidir.

> [!IMPORTANT]
> **Yasal Uyarı:** Bu proje bağımsız bir topluluk çalışmasıdır. Grinding Gear Games (GGG) ile resmi bir bağımız bulunmamaktadır. Tamamen ücretsizdir.


* **Topluluk Destekli:** Türk oyuncular tarafından, Türk oyuncular için hazırlandı. Katkıda bulunmak için [🤝 Katkıda Bulunun](#-katkıda-bulunun) bölümüne gidebilirsiniz.

---

## 🛠 Kurulum ve Kullanım

### 📽 Videolu Kurulum Rehberi
Kurulumda zorlanıyorsanız, adım adım videomuzu izleyebilirsiniz:

[![Exile-UI Kurulum Videosu](https://img.youtube.com/vi/TODO_VİDEO_ID_EKLEYECEĞİM/0.jpg)](https://www.youtube.com/watch?v=TODO_VİDEO_ID_EKLEYECEĞİM)
*(Not: Video henüz eklenmediyse aşağıdaki manuel adımları takip edin.)*

### 📝 Manuel Kurulum Adımları

1. **İndir:** Bu repodaki `data/tr` klasörünü bilgisayarınıza indirin.
2. **Dizine Git:** Exile-UI'ın kurulu olduğu ana klasörü açın ve içindeki `data` klasörüne girin.
3. **Kopyala:** İndirdiğiniz `tr` klasörünü buraya yapıştırın. Yol şu şekilde görünmelidir: `.../Exile-UI/data/tr/`
4. **Aktif Et:** Exile-UI'ı başlatın. **General** sekmesinden dil olarak **tr** seçin.
5. **Yeniden Başlat:** Değişikliklerin tam uygulanması için aracı kapatıp tekrar açın.

---

## 📊 Çeviri İlerleme Durumu

Projedeki çeviri sürecini şeffaf bir şekilde takip edebilmeniz için güncel durum aşağıdadır. İsminde "2" bulunan dosyalar, Path of Exile 2 için. *(Bu alan çeviriler yapıldıkça güncellenecektir.)*

### 🖥️ Temel Arayüz & İpuçları
- [x] `UI.txt` - **Tamamlandı**
- [ ] `client.txt`
- [ ] `help tooltips.json` - **Tamamlandı, son kontrol sağlanmalı.**
- [ ] `TLDR-tooltips.json`

### 📈 Act Takibi (leveltracker)
- [ ] `[leveltracker] areas.json`
- [ ] `[leveltracker] areas 2.json`
- [x] `[leveltracker] default guide.json` - **Tamamlandı**
- [ ] `[leveltracker] default guide 2.json`
- [ ] `[leveltracker] gems.json`
- [ ] `[leveltracker] gems 2.json`

### 🗺️ Harita ve Oyun Mekanikleri (Terim içerdikleri için çeviriye gerek yok fakat kontrol edilecekler.)
- [ ] `maps.json`
- [ ] `maps 2.json`
- [ ] `map-info.txt`
- [ ] `map-info 2.txt`
- [ ] `anoints.json`
- [ ] `anoints 2.json`
- [ ] `Betrayal.json`
- [ ] `essences.json`
- [ ] `mercenaries.json`
- [ ] `[sanctum] relics.json`
- [ ] `[sanctum] relics 2.json`
- [ ] `timeless jewels.json`
---

## 🌐 Neden Her Şey Türkçe Değil?

PoE evreninde global ticaret ve bilgi paylaşımı çok kritiktir. Bu yüzden **Hibrit** bir model izliyoruz:

| Kategori | Durum | Örnek |
| :--- | :--- | :--- |
| **Arayüz (UI)** |  Türkçe | Ayarlar, Butonlar, Rehber |
| **Bölgeler** |  İngilizce | *Mud Flats, Lioneye's Watch* |
| **Eşya İsimleri** |  İngilizce | *Tabula Rasa, Mageblood* |
| **Mekanik İsimleri** |  İngilizce | *Fusing, Chaos Orb, Lightning Arrow* |

**Neden?** Eğer "Mud Flats" haritasının ismini rehberde "Çamur Düzlükleri" olarak çevirirsek, rehberi takip ettiğiniz sırada, internette bir rehbere baktığınızda veya ticaret sitelerinde arama yaptığınızda karşılık bulamazsınız. Bu yöntemle hem aracı anlıyor hem de global terminolojiye sadık kalıyorsunuz. 

*Not: GGG Path of Exile 2 için çevirmen aradığını resmi olarak duyurdu, resmi Türkçe dil desteği sunulduğu an, terimlerin karşılıklarını resmi çeviriye uygun şekilde güncelleyeceğiz.*


---

## ❓ Sıkça Sorulan Sorular (SSS)

**S: Ban riski var mı?** <br>
C: Hayır. Bu sadece bir arayüz çeviri paketidir, oyun dosyalarına müdahale etmez. Sadece eklentinin kendi yazılarını değiştirir.

**S: Oyun güncellenince çeviri bozulur mu?** <br>
C: Exile-UI ana uygulaması güncellendiğinde yeni İngilizce satırlar eklenebilir. Bu durumda çeviriyi en kısa sürede güncelliyoruz. Repoyu takipte (Watch) kalarak güncellemelerden haberdar olabilirsiniz.

---

## 🤝 Katkıda Bulunun

Proje henüz gelişme aşamasındadır. Siz de destek olabilirsiniz:
* **Hata Bildirimi:** Hatalı veya anlamsız çevirileri [Issues](https://github.com/faadw/Exile-UI-Turkish/issues) kısmından bildirebilirsiniz.
* **Geliştirme:** Çeviriyi iyileştirmek için bir **Pull Request** gönderebilirsiniz.
* **Paylaşım:** Bu projeyi PoE Türkiye topluluklarında paylaşarak daha fazla oyuncuya ulaşmamıza yardımcı olabilirsiniz.

---

## 💬 İletişim

[![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/244173139167281154)
[![Steam](https://img.shields.io/badge/Steam-%231b2838.svg?style=for-the-badge&logo=steam&logoColor=white)](https://steamcommunity.com/id/realfaadw)
---

## 💎 Teşekkürler
* Ana aracın geliştiricisine (**[Lailloken](https://github.com/Lailloken)**) bu esnek yerelleştirme altyapısını sağladığı için teşekkürler.

---

<h1 align="center"><i>Stay sane, exile!</i></h1>
