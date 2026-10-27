# Equalang Zotero Çeviri Eklentisi

[![Release](https://img.shields.io/github/v/release/equalang/equalang-zotero-plugin)](https://github.com/equalang/equalang-zotero-plugin/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/equalang/equalang-zotero-plugin/total)](https://github.com/equalang/equalang-zotero-plugin/releases)
[![Zotero](https://img.shields.io/badge/Zotero-7%20%7C%208%20%7C%209%20%7C%2010-CC2936)](https://www.zotero.org)
[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20macOS-555555)](#sıkça-sorulan-sorular)

[English](../README.md) · [简体中文](README.zh-CN.md) · [繁體中文](README.zh-TW.md) · [日本語](README.ja.md) · [한국어](README.ko.md) · [Español](README.es.md) · [Français](README.fr.md) · [Deutsch](README.de.md) · [Português](README.pt.md) · [Italiano](README.it.md) · [Русский](README.ru.md) · [Polski](README.pl.md) · **Türkçe** · [Tiếng Việt](README.vi.md) · [Bahasa Indonesia](README.id.md) · [ไทย](README.th.md) · [हिन्दी](README.hi.md) · [العربية](README.ar.md)

[En son sürümü indirin](https://github.com/equalang/equalang-zotero-plugin/releases/latest) · [Resmî web sitesi](https://equalang.com/tr/extension/zotero?utm_source=github) · [Fiyatlandırma](https://equalang.com/tr/pricing?utm_source=github) · [Değişiklik günlüğü](../CHANGELOG.md)

> **Anahtar kelimeler:** Zotero çeviri eklentisi, Zotero PDF çevirisi, akademik literatür çevirisi, makale çevirisi, düzeni koruyan PDF çevirisi, yan yana karşılaştırmalı çeviri, seçilen metni çevirme, Word çevirisi, PPT çevirisi, Excel çevirisi, akademik çeviri, zotero plugin, zotero translate, pdf translator

**Tek tıkla çevir, yan yana oku.** Equalang Zotero eklentisi, PDF ve diğer belgelerin çevirisinin yanı sıra seçilen metinlerin çevirisini de destekler: Tüm makaleyi çevirmek için eke sağ tıklamanız yeterlidir; çeviri özgün düzeni korur ve orijinal ögenin altına ek olarak iliştirilir. Okuyucuda metin seçtiğinizde, çeviri ve sözlük anlamları anında açılır pencerede görünür.

![Solda orijinal metin, sağda çeviri; bir kelime seçildiğinde anlamı anında açılır pencerede görünür](../images/reader-bilingual.png)

## Özellikler

- **Belge çevirisi**: Çevirmek için bir PDF, Word, PowerPoint veya Excel ekine sağ tıklamanız yeterlidir. Çeviri özgün düzeni korur ve orijinal ögenin altına ek olarak iliştirilir; PDF belgeleri için orijinal ve çeviriyi yan yana okuyabileceğiniz karşılaştırmalı bir sürüm de oluşturulabilir.
- **Seçim çevirisi**: Okuyucuda metin seçtiğiniz anda çeviri açılır pencerede görünür; tek bir kelime seçildiğinde ise anlamı, sesletimi ve örnek cümleler de sunulur.
- **Arka planda çeviri**: Zotero'dan istediğiniz zaman çıkabilirsiniz; tamamlanmamış görevler bir sonraki başlatmada devam eder ve çeviri yine de orijinal ögenin altına eklenir.
- **Web sitesiyle ortak kredi kullanımı**: Belge çevirisi başlamadan önce harcanacak tahmini kredi ve mevcut bakiyeniz gösterilir; iptal edilen görevlerden kredi kesilmez.

## Kurulum

1. **Eklenti dosyasını indirin**: [Sürümler sayfasına](https://github.com/equalang/equalang-zotero-plugin/releases/latest) gidin ve `equalang.xpi` dosyasının en son sürümünü indirin; dosyayı arşivden çıkarmanız gerekmez.
2. **Zotero eklenti yöneticisini açın**: Zotero menüsünde «Araçlar → Eklentiler» seçeneğini belirleyin.
3. **Dosyadan yükleyin**: Sağ üstteki dişli simgesine tıklayın, «Install Plugin From File…» seçeneğini belirleyin ve indirdiğiniz dosyayı seçin; ayrıca dosyayı doğrudan bu eklenti penceresine de sürükleyebilirsiniz.
4. **Equalang'e giriş yap**: Kurulum tamamlandığında bir karşılama penceresi açılır; «Giriş yap veya kaydol» seçeneğine tıklayın ve tarayıcınızda giriş işlemini tamamlayın. Yeni hesaplara ücretsiz kredi hediye edilir.

Bundan sonra eklenti Zotero ile birlikte otomatik olarak güncellenir; dilerseniz «Araçlar → Eklentiler» altındaki dişli menüsünden güncellemeleri elle de denetleyebilirsiniz.

## Kullanım

- **Belgeleri çevirme**: Bir ögeye veya eke sağ tıklayın, «Equalang ile Belgeyi Çevir…» seçeneğini belirleyin, hedef dili ve tahmini krediyi onayladıktan sonra işlemi başlatın. İlerleme durumu sağdaki «Equalang» bölmesinde gösterilir; ayrıca «Araçlar → Equalang → Çeviri Görevleri…» menüsünden de takip edilebilir.

  ![Sağ tık menüsünde Equalang ile çeviri](../images/context-menu.png)

- **Yan yana karşılaştırmalı okuma**: Karşılaştırmalı sürümü açın ve okuyucuda «Görünüm → İki sayfalı görünüm → Tek numaralı» yolunu seçin; orijinal ve çeviri metin yan yana görüntülenecektir.
- **Seçim çevirisi**: Okuyucuda metni seçmeniz yeterlidir. Dilerseniz ayarlardan «Önce bir Çevir düğmesi göster» olarak değiştirip yalnızca tıkladığınızda çevrilmesini sağlayabilirsiniz.
- **Ayarlar**: «Araçlar → Equalang → Ayarlar...» menüsünden hedef dili, PDF için karşılaştırmalı mı yoksa yalnızca çeviri mi olacağını, çevirilerin nereye kaydedileceğini, «Tamamlandığında çeviriyi aç» seçeneğini ve PDF formül düzeni optimizasyonunu (ek kredi harcar) belirleyebilirsiniz.

## Sıkça Sorulan Sorular

**Hangi Zotero sürümleri ve işletim sistemleri destekleniyor?**

Zotero 7, 8, 9 ve 10 desteklenir; hem Windows hem de macOS üzerinde kullanılabilir.

**Ücretlendirme nasıl yapılır?**

Eklentiyi yüklemek ücretsizdir. Çeviri işlemleri Equalang web sitesiyle aynı kredi bakiyesini kullanır ve [web sitesindeki fiyatlar](https://equalang.com/tr/pricing?utm_source=github) üzerinden düşülür. Belge çevirisi başlamadan önce harcanacak tahmini kredi ve mevcut bakiyeniz gösterilir; iptal edilen görevlerden kredi kesilmez. Yeni hesaplara ücretsiz kredi hediye edilir.

**Çevrilen dosyalar nerede saklanır?**

Çevrilen belge varsayılan olarak orijinal ögenin altına ek olarak kaydedilir ve Zotero ile eşzamanlanır; ayarlardan bunu bilgisayarınızdaki bir klasöre kaydedip ögeye bağlantı verecek şekilde de değiştirebilirsiniz (yalnızca «Kitaplığım» için geçerlidir).

## Bağlantılar

- [Equalang resmî sitesi](https://equalang.com/tr?utm_source=github) · [Zotero eklenti sayfası](https://equalang.com/tr/extension/zotero?utm_source=github) · [Fiyatlandırma](https://equalang.com/tr/pricing?utm_source=github) · [Gizlilik Politikası](https://equalang.com/tr/legal/privacy?utm_source=github) · [Kullanım Şartları](https://equalang.com/tr/legal/terms?utm_source=github)
- [Equalang tarayıcı uzantısı](https://equalang.com/tr/extension?utm_source=github): Web sayfaları, video altyazıları ve manga çevirisi
- Sorularınız için: <support@equalang.com>

Bu depoda eklentinin kurulum paketleri (bkz. [Releases](https://github.com/equalang/equalang-zotero-plugin/releases)) ve değişiklik günlükleri yayımlanmaktadır.
