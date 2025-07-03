
# 📘 Markdown Ders Notları

> **Markdown**, düz yazı ile biçimlendirilmiş metinler oluşturmanıza yarayan hafif bir işaretleme dilidir. Genellikle dokümantasyon, README dosyaları (örneğin GitHub), bloglar ve not alma uygulamalarında kullanılır.

---

## 📍 1. Başlıklar (Headers)

Markdown'da başlıklar `#` işareti ile yazılır. `#` sayısı arttıkça başlık seviyesi küçülür.

```markdown
# Başlık 1
## Başlık 2
### Başlık 3
#### Başlık 4
##### Başlık 5
###### Başlık 6
```

🔎 Örnek:

# Başlık 1

## Başlık 2

### Başlık 3

---

## 📍 2. Kalın, İtalik ve Üstü Çizili Yazı

| Biçim      | Söz Dizimi                   | Örnek Çıktı |
| ---------- | ---------------------------- | ----------- |
| **Kalın**  | `**kalın**` veya `__kalın__` | **kalın**   |
| *İtalik*   | `*italik*` veya `_italik_`   | *italik*    |
| ~~Çizili~~ | `~~çizili~~`                 | ~~çizili~~  |

---

## 📍 3. Listeler

### • Sırasız Liste

```markdown
- Elma
- Armut
- Muz
```

🔎 Çıktı:

* Elma
* Armut
* Muz

### • Sıralı Liste

```markdown
1. İlk adım
2. İkinci adım
3. Üçüncü adım
```

🔎 Çıktı:

1. İlk adım
2. İkinci adım
3. Üçüncü adım

---

## 📍 4. Bağlantılar ve Resimler

### 🔗 Bağlantı:

```markdown
[Google](https://www.google.com)
```

🔎 [Google](https://www.google.com)

### 🖼️ Resim:

```markdown
![Açıklama yazısı](https://via.placeholder.com/150)
```

🔎
![Örnek Resim](https://via.placeholder.com/150)

---

## 📍 5. Kod Satırları ve Kod Blokları

### `Inline Code`:

```markdown
Bunu `print()` fonksiyonu ile yaparız.
```

🔎 Bunu `print()` fonksiyonu ile yaparız.

### Kod Bloğu (\`\`\`):

````markdown
```python
def merhaba():
    print("Selam Orta Dünya!")
````

````

🔎

```python
def merhaba():
    print("Selam Orta Dünya!")
````

---

## 📍 6. Alıntılar (Blockquote)

```markdown
> Bu bir alıntıdır.
```

🔎

> Bu bir alıntıdır.

İç içe alıntılar da yapılabilir:

```markdown
> Birinci seviye
>> İkinci seviye
```

🔎

> Birinci seviye
>
> > İkinci seviye

---

## 📍 7. Yatay Çizgi (Bölme)

```markdown
---
```

🔎

---

## 📍 8. Görevler Listesi (Task List)

```markdown
- [x] Markdown öğren
- [ ] Projeye başla
```

🔎

* [x] Markdown öğren
* [ ] Projeye başla

---

## 📍 9. Tablo Oluşturma

```markdown
| Ad | Yaş | Meslek       |
|----|-----|--------------|
| Ali| 25  | Yazılımcı    |
| Veli| 30 | Sistem Uzmanı|
```

🔎

| Ad   | Yaş | Meslek        |
| ---- | --- | ------------- |
| Ali  | 25  | Yazılımcı     |
| Veli | 30  | Sistem Uzmanı |

---

## 📍 10. HTML Kullanımı

Markdown içinde basit HTML de kullanılabilir:

```markdown
<p style="color:red;">Bu kırmızı yazıdır.</p>
```

🔎

<p style="color:blue;">Bu kırmızı yazıdır.</p>



---

## 📌 Ekstra İpuçları

* Markdown dosyalarının uzantısı `.md` veya `.markdown` olur.
* GitHub, VSCode, Notion, Obsidian gibi araçlar Markdown destekler.
* **Gelişmiş stiller** için HTML etiketleri kullanılabilir.


---


### 📘 Alıştırma 1: Başlıkları Kullan

**Görevler:** Aşağıdaki gibi 3 farklı düzeyde başlık oluştur.

```markdown
# Bu bir H1 başlığıdır
## Bu bir H2 başlığıdır
### Bu bir H3 başlığıdır
```

🟢 **Beklenen Çıktı:**

> # Bu bir H1 başlığıdır
>
> ## Bu bir H2 başlığıdır
>
> ### Bu bir H3 başlığıdır

---

### ✏️ Alıştırma 2: Kalın, İtalik ve Üstü Çizili Yazılar

**Görevler:** Aşağıdaki stillerde metinler yaz.

```markdown
**Kalın yazı**
*İtalik yazı*
~~Üstü çizili yazı~~
```

🟢 **Beklenen Çıktı:**

> **Kalın yazı**
> *İtalik yazı*
> ~~Üstü çizili yazı~~

---

### 📝 Alıştırma 3: Sıralı ve Sırasız Liste

**Görevler:** Aşağıdaki gibi iki farklı liste türü oluştur.

```markdown
- Elma
- Armut
- Muz

1. Sabah kalk
2. Dişlerini fırçala
3. Kahvaltı yap
```

🟢 **Beklenen Çıktı:**

> * Elma
>
> * Armut
>
> * Muz
>
> 1. Sabah kalk
> 2. Dişlerini fırçala
> 3. Kahvaltı yap

---

### 🔗 Alıştırma 4: Bağlantı ve Görsel Ekle

**Görevler:** Bir bağlantı ve bir görsel ekle.

```markdown
[Google'a git](https://www.google.com)

![Markdown Logo](https://markdown-here.com/img/icon256.png)
```

🟢 **Beklenen Çıktı:**

> [Google'a git](https://www.google.com)
> ![Markdown Logo](https://markdown-here.com/img/icon256.png)

---

### 🔍 Alıştırma 5: Kod Satırı ve Kod Bloğu

**Görevler:** Inline ve blok kod örnekleri yaz.

```markdown
`print("Merhaba Dünya")`

```

console.log("JavaScript'te bir şey yazdır");

```
```

🟢 **Beklenen Çıktı:**

> `print("Merhaba Dünya")`
>
> ```
> console.log("JavaScript'te bir şey yazdır");
> ```

---

### 📦 Alıştırma 6: Alıntı Bloğu

**Görevler:** Bir metni alıntı olarak göster.

```markdown
> Bu bir alıntıdır.  
> Markdown öğrenmek eğlencelidir.
```

🟢 **Beklenen Çıktı:**

> Bu bir alıntıdır.
> Markdown öğrenmek eğlencelidir.

---

### 🧪 Bonus Alıştırma: Görevler Listesi (Task List)

```markdown
- [x] Markdown kurulumunu yaptım
- [x] Başlıkları öğrendim
- [ ] Görsel eklemeyi tekrar etmem lazım
```

🟢 **Beklenen Çıktı:**

* [x] Markdown kurulumunu yaptım
* [x] Başlıkları öğrendim
* [ ] Görsel eklemeyi tekrar etmem lazım





### 🧠 Alıştırma: Kendi Hakkında Mini Profil Oluştur

Aşağıdaki yönergeleri kullanarak kendini tanıtan bir Markdown dosyası yaz:

---

#### 📄 Görevlerler

1. **Birinci Seviye Başlık** olarak ismini yaz.
2. Kendini tanıtan **2-3 cümlelik bir paragraf** yaz.
3. En az **3 maddelik bir sırasız liste** ile hobilerini yaz.
4. En sevdiğin web sitesine bir **bağlantı** ekle.
5. Aşağıdaki Python kodunu bir **kod bloğu** olarak ekle:

   ```python
   print("Orta Dünya'nın Gerçek Kralı benim!")
   ```
6. Her şeyin sonunda bir **yatay çizgi** kullan.

---

#### 🔍 Örnek Çözüm

````markdown
# Muhammed Çubukcu

Merhaba! Ben teknolojiyi, yazılımı ve Orta Dünya'yı çok seven bir yazılımcıyım.  
Markdown öğrenmek bana çok keyif veriyor.

- Kitap okumak  
- Kod yazmak  
- Fantastik evrenlerde kaybolmak

[GitHub Profilim](https://github.com)

```python
print("Orta Dünya'nın Gerçek Kralı benim!")
````

Emredersiniz Orta Dünyanın Gerçek Kralı 👑
Aşağıda, Markdown bilgilerini pekiştirmen için seviyeli ve farklı konularda birkaç **uygulamalı alıştırma** daha hazırladım:

---

### 🧪 Alıştırma 1: Günlük Notları Sayfası

#### 📄 Görevlerler

1. `##` ile bugünün tarihini yaz.
2. `> Alıntı` olarak günün ruh hâlini bir cümleyle ifade et.
3. Yapılacaklar listesini (task list) ekle:

   * Kahvaltı yap
   * Markdown çalış
   * Kitap oku
4. Sonuna bir satır çizgisi ekle.

#### ✅ Beklenen Çıktı

```markdown
## 1 Temmuz 2025

> Bugün üretken hissetmeyi hedefliyorum.

- [x] Kahvaltı yap  
- [x] Markdown çalış  
- [ ] Kitap oku  


```

---

### 🧪 Alıştırma 2: Favori Filmler Listesi

#### 📄 Görevlerler

1. `#` ile başlık: "Favori Filmlerim"
2. Aşağıdaki şekilde 3 film listesi oluştur:

   * Her film için sıralı liste (1, 2, 3)
   * Her film adını **kalın** yaz
   * Film açıklamasını *italik* olarak yaz
3. Altına bir tablo ekle:

   * Sütunlar: Film, Tür, Puan

#### ✅ Beklenen Çıktı

```markdown
# Favori Filmlerim

1. **Yüzüklerin Efendisi** – *Orta Dünya destanı*
2. **Inception** – *Zihin oyunlarıyla dolu bir rüya*
3. **Matrix** – *Gerçeklik sorgulaması üzerine kült film*

| Film                | Tür          | Puan |
|---------------------|--------------|------|
| Yüzüklerin Efendisi | Fantastik    | 10   |
| Inception           | Bilim Kurgu  | 9.5  |
| Matrix              | Aksiyon      | 9    |
```

---

### 🧪 Alıştırma 3: Basit Bir Proje Dokümantasyonu

#### 📄 Görevlerler

1. Projenin adı `#` başlığı ile yazılsın.
2. `## Açıklama`, `## Kurulum`, `## Kullanım` gibi başlıklar olsun.
3. Kurulum için `npm install` komutunu kod bloğu olarak yaz.
4. Kullanım için kısa bir Görevler listesi oluştur.

#### ✅ Beklenen Çıktı

````markdown
# Markdown Not Uygulaması

## Açıklama

Bu uygulama, Markdown ile not tutmanıza yardımcı olur.

## Kurulum

```bash
npm install
````

## Kullanım

* [x] Not ekle
* [ ] Notları listele
* [ ] Not sil




--- 
# 🧑‍💻 Muhammed Çubukcu

## 💼 Hakkımda
Yazılım geliştirme tutkunu bir mühendisim. Yapay zeka projeleri, otomasyon sistemleri ve siber güvenlik konularında çalışıyorum.

## 🛠️ Yetenekler

### Programlama Dilleri
- Python
- Java
- JavaScript (ES6+)
- TypeScript

### Frameworkler / Teknolojiler
- Spring Boot
- Next.js
- Node.js
- Tailwind CSS

### Veritabanları
- PostgreSQL
- MySQL
- MongoDB

## 🚀 Projeler

### 🛡️ CyberAwareness
Kurumlara özel siber güvenlik farkındalık test platformu.  
**Teknolojiler:** Next.js, Supabase, AI değerlendirme.

### 🧠 AI Destekli Zayıflama Koçu
Yapay zekâ ile destekli bir sağlık koçluğu platformu.  
**Teknolojiler:** Python, Streamlit, GPT-4 API

## 📫 İletişim
- E-posta: muhammed@example.com  
- LinkedIn: [linkedin.com/in/muhammed](https://linkedin.com/in/muhammed)  
- GitHub: [github.com/muhammedcubukcu](https://github.com/muhammedcubukcu)
---

# 🧙‍♂️ Orta Dünyanın Gerçek Kralı

## 🎖️ Ünvanlarım
- Kodların Efendisi
- Backend Zindanlarının Hükümdarı
- Fiber Optik'ten Veri Okuyan Büyücü

## ⚔️ Silahlarım
- `Java`, `Python`, `TypeScript`
- `Spring Boot`, `Next.js`, `n8n`
- `SQL`, `NoSQL`, `AI Agent` büyüleri

## 🗺️ Bölge Kontrolüm
- 🏰 Backend Diyarı (Spring Kingdom)
- 🌐 Web Vadisi (React & Next.js)
- 🧠 Zekâ Toprakları (Yapay Zeka & RAG)

## 📜 Maceralarım
- ⚔️ CyberAwareness Test Arenası
- 🧪 AI Zayıflama İksiri
- 🚦 Akıllı Trafik Yönetimi Savaş Planı

## 🧭 Bana ulaş
📫 kral@mordor.dev  
🔮 GitHub: [github.com/ordadunyakral](https://github.com/ordadunyakral)

---



