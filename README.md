# TWIN
# TWIN | Antalya 2040

> **İklim kararlarını şehre uygulamadan önce sınayın.**  
> *Test climate decisions before implementing them in the city.*

## Proje hakkında

TWIN (İklim İkizi), şehirlerin iklim uyum müdahalelerini uygulamadan önce dijital ortamda değerlendirmesine yardımcı olması hedeflenen, yapay zekâ destekli bir karar destek sistemidir.

Proje; yerel ısı risklerini tahmin etmeyi, şehrin kuş bakışı ve üç boyutlu dijital modelinde farklı müdahaleleri simüle etmeyi ve bu seçenekleri ısı, su ihtiyacı ve maliyet açısından karşılaştırmayı amaçlar. TWIN’in odağı yalnızca “sıcaklığı nasıl azaltırız?” sorusu değil; **“Hangi müdahale, hangi bölgede ve hangi kaynaklarla daha uygun olabilir?”** sorusudur.

Antalya’da, kullanılabilir veriler doğrulandıktan sonra belirlenecek bir pilot bölgede çalışılması planlanmaktadır.

## Problem

Yoğun yapılaşma, yetersiz gölge ve sınırlı yeşil alan, kent içindeki sıcaklık maruziyetini mahalleden mahalleye farklılaştırabilir. Serinletme amacıyla yapılacak müdahalelerin de su ve bütçe ihtiyacı vardır. Örneğin ağaçlandırma gölge sağlayabilirken su gerektirir; serin çatılar, gölgelikler veya geçirgen yüzeyler farklı koşullarda daha uygun olabilir.

Şehirlerin bu seçenekleri uygulamaya geçmeden önce birlikte değerlendirebileceği, veri ve varsayımlarını açıkça gösteren araçlara ihtiyaç vardır.

## Çözüm

TWIN, ısı riski tahminini şehir simülasyonu ve kaynak optimizasyonuyla bir araya getirmeyi hedefler:

1. **Veriyi inceleme:** Uydu ve Dünya gözlem verileri, meteorolojik geçmiş, arazi örtüsü, bitki yoğunluğu ve açık harita/bina verileri değerlendirilir.
2. **Isı riskini tahmin etme:** Yapay zekâ modelleriyle yerel ölçekte ısı riski görünümü oluşturulması hedeflenir.
3. **Dijital şehir modeli:** Riskler, Antalya’daki pilot alanın kuş bakışı ve üç boyutlu şehir görünümünde sunulur.
4. **Müdahaleleri senaryolaştırma:** Kullanıcı; sıcak hava dalgası ve su kısıtı gibi senaryoları seçerek ağaçlandırma, serin çatı, gölgelik ve geçirgen yüzey seçeneklerini karşılaştırabilir.
5. **Alternatifleri değerlendirme:** Senaryoların tahmini ısı maruziyeti, su ihtiyacı ve maliyet açısından karşılaştırılması; su ve bütçe gibi kaynak kısıtlarının dikkate alınması amaçlanır.

**Yapay zekâ ısı riskini tahmin etmeye, simülasyon müdahale senaryolarını sınamaya, optimizasyon ise kısıtlı kaynaklar altında alternatif planları karşılaştırmaya odaklanır.**

## Hedef kullanıcılar

- Belediyelerin şehir planlama, park ve bahçeler, su ve enerji yönetimi birimleri
- İklim uyum planları hazırlayan kurumlar
- Okullar ve sağlık kuruluşları
- Sıcak hava dalgalarına karşı daha kırılgan olabilecek yaşlılar, çocuklar, kronik rahatsızlığı bulunan kişiler ve açık alanda çalışanlar

## Planlanan veri ve yöntemler

Yararlanılması değerlendirilecek veri türleri:

- NASA uydu ve Dünya gözlem verileri
- Yüzey sıcaklığı, arazi örtüsü ve bitki yoğunluğu verileri
- Geçmiş meteorolojik ölçümler
- Açık harita ve bina verileri

Teknoloji ve yöntem olarak coğrafi bilgi sistemleri (CBS/GIS), web tabanlı harita, etkileşimli şehir simülasyonu, yapay zekâ ve optimizasyon yöntemlerinin kullanılması hedeflenmektedir. React, TypeScript ve Python, ekipte bulunan yazılım yetkinlikleri arasındadır.

**Veri kaynaklarının erişilebilirliği, lisansı, kapsama alanı ve çözünürlüğü geliştirme sürecinde doğrulanacaktır.** Bir kaynak doğrulanmadan kullanılmış veya hazırmış gibi sunulmayacaktır.

## Etki nasıl ölçülecek?

TWIN’de farklı müdahale senaryolarının aşağıdaki ölçütlerle karşılaştırılması hedeflenmektedir:

- Tahmini ısı maruziyetindeki değişim
- Yüksek ısı riskine maruz kalan kişi sayısı
- Müdahalelerin su ihtiyacı
- Tahmini uygulama maliyeti
- Veri elverdiğinde öncelikli gruplar ve kritik noktalar üzerindeki olası etki

Model tahminleri, doğrulanabildiği ölçüde uydu görüntüleri ve meteorolojik ölçümlerle karşılaştırılacaktır. Gerçek ölçümler ile model tahminleri açıkça birbirinden ayrılacaktır.

## Creathon sonunda hedeflenen çıktı

Antalya’da verisi doğrulanmış bir pilot alanı gösteren, kullanıcıların farklı sıcaklık ve su kısıtı senaryolarını seçip müdahaleleri haritada karşılaştırabildiği çalışan bir web prototipi hedeflenmektedir. Prototipte en az bir temel ısı riski görünümü ve çalışan bir müdahale senaryosu karşılaştırması bulunması amaçlanmaktadır.

Bunlara ek olarak veri kaynakları ve sınırlılıkları, etki ölçüm yaklaşımı, teknik geliştirme yol haritası ve ilk iş modeli taslağının sunulması planlanmaktadır.

## Ekip

### Betül Kaya — Takım kaptanı

**Kurum:** Çukurova Üniversitesi (mezun)  
**Bölüm:** Bilgisayar ve Öğretim Teknolojileri Eğitimi (BÖTE)  
**Rol:** Proje yönetimi, yapay zekâ ve veri analizi, web geliştirme, UI/UX tasarımı, dijital ikiz arayüzü ve 3B simülasyon geliştirme.

React, TypeScript, Python, web geliştirme ve etkileşimli arayüzler alanlarında deneyime sahiptir. Yapay Zekâ ve Teknoloji Akademisi kapsamında veri bilimi eğitimleri almış; Samsung Innovation Campus yapay zekâ eğitim programına Türkiye genelinde kabul edilen 75 öğrenciden biri olarak katılmıştır.

### İrem Soytürk — Takım üyesi

**Kurum:** Çukurova Üniversitesi  
**Bölüm:** Makine Mühendisliği, 3. sınıf  
**Rol:** Şehir ve çevre sistemlerinin modellenmesi, iklim müdahalelerinin teknik değerlendirilmesi ve simülasyon senaryolarının geliştirilmesi.

Lise döneminde TEKNOFEST kapsamında iki kez finalist olmuş; üniversite eğitiminde teknoloji yarışmalarına ve proje çalışmalarına katılmayı sürdürmektedir.

### Elif Kütükoğlu — Takım üyesi

**Kurum:** Alparslan Türkeş Bilim ve Teknoloji Üniversitesi  
**Bölüm:** Elektrik-Elektronik Mühendisliği, 2. sınıf  
**Rol:** Teknik araştırma, veri kaynaklarının incelenmesi, iklim verilerinin değerlendirilmesi ve sistem geliştirme süreçlerine katkı.

Elektrik, donanım ve yazılım alanlarında kendini geliştirerek projeye disiplinler arası bir teknik bakış açısı kazandırmaktadır.

## Ekip deneyimi

Takım kaptanı Betül Kaya’nın proje ve yarışma deneyimleri arasında:

- TEKNOFEST 2025 Mavi Vatan Makale Yarışması — Türkiye birinciliği
- TEKNOFEST 2026 NSosyal Sosyal İnovasyon Yarışması — Türkiye ikinciliği
- Brisa Fikir Maratonu — birincilik
- UNDP destekli DIGIHACK4ANATOLIA Uluslararası Hackathonu — ikincilik
- Fikrim Gelecek Yarışması — ikincilik
- TRT Geleceğin İletişimcileri Yarışması — üç projeyle finalistlik
- Turkcell CodeNight — finalistlik
- Samsung Innovation Campus programı kapsamında düzenlenen hackathon — ikincilik
- TÜBİTAK 2209-A ve 2242 proje çalışmalarında araştırma ve proje geliştirme deneyimi

Üç takım üyesi de T3 Vakfı bünyesinde eğitmenlik ve mentorluk faaliyetlerinde bulunarak bilgi paylaşımı ve takım çalışması deneyimi kazanmaktadır.

## Geliştirme ve doğrulama yaklaşımı

TWIN’in pilot alanı, veri kaynakları, model yaklaşımı ve simülasyon varsayımları geliştirme sürecinde doğrulanacaktır. Gerçek veriyle desteklenmeyen haritalar ve çıktılar temsili senaryo olarak etiketlenecek; doğrulanmış sonuçlar elde edilmeden başarı veya etki rakamı paylaşılmayacaktır.

---

## English summary

TWIN | Antalya 2040 is a planned AI-supported climate decision-support project. It aims to combine local heat-risk estimation with a digital city model, allowing users to compare climate adaptation scenarios—such as trees, cool roofs, shade structures and permeable surfaces—under water and budget constraints.

The project will focus on a data-verified pilot area in Antalya. Its intended outputs include an interactive web prototype and transparent documentation of data sources, assumptions, limitations and impact measures. Model estimates will be distinguished from observed data and validated where suitable measurements are available.
