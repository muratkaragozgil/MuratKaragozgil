# Tweet stil rehberi: @levelsio + @marclou → @mrtkrgzgl

Kaynak: 12 Kasım 2026'da çekilen 115 tekil tweet.

- levelsio: 40 tweet, 20 reply
- marclou: 35 tweet, 20 reply

Ham örnekler `data/samples.json` dosyasında. Retweetler alınmadı. Tweetler iki parça halinde çekildi: en yeniler ve son 6 ayda çok beğenilenler.

---

## 1. Ortak mantık

1. **Hep birinci tekil şahıs.** "I built / I made / I got / I told him" diye başlarlar. Genel tavsiye vermezler, kendi başlarına geleni anlatırlar. Çıkacak bir ders varsa en sona tek satır olarak koyarlar.
2. **İlk satır kancadır.** "Show more"dan önce görünen tek satır o. Kullandıkları kanca türleri:
   - İtiraf: `I made a mistake.`
   - Olay: `So... it happened.`
   - Rakam: `I made $107,142 in October 2026`
   - İddia: `X should have a zero tolerance policy for AI replies`
   - Sürpriz: `I got a serious offer of $2.5M for X, all cash.`
3. **Rakamlar gerçek ve tam.** `$300/mo`, `252 million visitors`, `850 AED (~$230)`, `4 hours` karşısında `336 hours`. Yuvarlak değil, tam rakam güven veriyor.
4. **Her satırda bir cümle, aralarda boş satır.** Uzun tweetlerin yaklaşık %70'i boş satırlı paragraflarla yazılmış. Bir satır 8 ila 12 kelime.
5. **Hashtag kullanmazlar.** 115 tweetin hiçbirinde yok. Link de nadir, genelde sadece lansmanlarda.
6. **Ürün hikayenin içinde geçer, reklam cümlesi kurulmaz.** Örnekler: `🏡 Interior AI turns it into a walkable 3d space`, `⭐️ TrustMRR — $42,531`.
7. **Gündemi kullanırlar.** Haberi quote'layıp tek cümle yorum eklerler.
   - `I told you, they will try eat all industries one by one` (7.1K beğeni)
   - `SaaS is so dead` (1.4K beğeni)
8. **Zıtlık ve paralel yapı.**
   - `It's never been this easy to build software` / `And never this hard to make money with it` (9.9K)
   - `Voice and text messages are async` / `Calls are sync and destroy my day` (1.9K)
9. **İşi ve hayatı karıştırırlar.** Kahve makinesi, PS5, WoW, spor salonu, evlilik, uyku. İnsanlar ürünü değil kişiyi takip ediyor.
10. **Çok reply atarlar, kısa ve sıcak tutarlar.** Gün içinde onlarca reply var. Reply büyümenin yarısı.
11. **Çoğunluk tespit, reklam değil.**
    - levelsio: 40 tweetin 8'i kendi işiyle ilgili. En çok beğenilen 20 tweetinden sadece biri öyle (masraf dökümü).
    - marclou: 35 tweetin yaklaşık üçte birinde ürün geçiyor, ama hep bir hikaye, rakam ya da espri içinde. "Şunu kullanın" diyen tek bir tweet yok.
    - İkisinde de en çok beğenilenler tespitler: `never been this easy ... never this hard`, `the end of UI for SaaS`, Apple eleştirisi, `X should have a zero tolerance policy for AI replies`.

---

## 2. @levelsio'nun sesi

- **Konuşur gibi yazar, cilalamaz.** Uzun ve virgüllü cümleler kurar, küçük yazım hatalarını düzeltmez ("nopw", "mpstly").
- **Son satırda nokta yok** (%0). Cümle bitince satır da biter.
- **Kelime tekrarıyla vurgular:** `Very very very cool`, `really really really good`, `never ever`.
- **Emojiler:**
  - Tweetin başında konu etiketi olarak: 💸 para, ✨ yeni özellik, ⏰ zaman.
  - Ürün adının önünde: `🏡 Interior AI`.
  - Sonda: 😊 🙏 😍 🤯 😂, bazen üçlü `😊😊😊`.
- **Butonları köşeli parantezle yazar:** `[ Render ]`, `[ 🎨 Style ]`.
- **Sert iddianın sonuna "I think" ekler** ama geri adım atmaz.
- **Build in public zinciri kurar.** Tweetlerinin %82'si quote, bunların yaklaşık yarısı kendi önceki tweeti. Her güncelleme bir öncekini quote'lar:
  - `Okay it works...` (`Next:` listesiyle)
  - `⏰ 3 hours later I have it working as a feature!`
  - `✨ Improved the ...` / `LIVE now on 🏡 Interior AI for all users 😊 🙏`
- **Kişisel kuralları kesin konuşur:** `I will never ever do calls except with family`.
- **Hikaye anlatırken:**
  - Diyalogları ayrı satırlarda, tırnak içinde verir.
  - Kendini saf biri gibi gösterir ("naive Dutch guy").
  - Vurucu bir sonla kapatır (☠️), ardından genel çıkarımı yazır.
- **Maliyet şeffaflığı:** Kalem kalem tasarruf listesi yapar. Araçları fiyatıyla verir (`Hetzner`, `Tailscale`, `Cloudflare Tunnel`).
- **Kendi hesapladığı karşılaştırmaları kullanır:** `~100x more dangerous than flying commercial`.
- **Reply'ları:**
  - Ortalama 40 karakter.
  - Örnekler: `Yesss!`, `Very cool`, `Oh smart man, thx I will try that`, `Ok I stand corrected ... TIL!`
  - Emoji kullanmaz, `:D` kullanır. Bazen 3-4 satırlık bir gözlem paylaşır.

## 3. @marclou'nun sesi

- **Temiz ve kısa cümleler kurar.** Satır başına yaklaşık 8 kelime. Son satırın %34'ü noktayla bitiyor.
- **Hikaye sırası:** kanca → bağlam → gerilim (`But I completely missed the other side.`) → farkına varma → karar → ders → ❤️
- **Kırılganlık:** `And honestly it hurts to read`, `That's my mistake.`
- **Alçakgönüllülük:** `I'm an average programmer` / ... / `But I'm pretty great at being me 😁`
- **Hikayeyi liste olarak anlatır.**
  - `It took:` / `- 4 hours for my agent to build it` / `- 336 hours for Apple to review it` (espri rakamlarda saklı)
  - Numaralı adımlar da kullanır (VIVO iadesi 1'den 7'ye).
- **Aylık gelir raporu formatı:**
  - Başlık: `I made $X in <ay>`
  - Her satırda bir ürün: emoji, ad, `$`
  - Tek satırlık özet: `16 revenue streams with 0 employees, 90% profit margins, and time for the gym every day.`
  - Kapanış: `A new personal record, I think 🤗`
- **Eleştirmenleri tırnakla alıntılar, 3 kelimeyle cevap verir:** `"You can't vibe code a profitable SaaS"` ... `Do what you can't.`
- **Mizah teknikleri:**
  - Sahte drama: `I was horrified by what I saw.` / `The situation was critical.` / `I could finally breathe again.` (konusu sadece responsive bug).
  - Greentext: `> be a basement dweller` / `> vibe code a beehiiv alternative` / `> be more profitable than beehiiv on day 1`
  - Süreğen espri: bodrum ("basement"), WoW, Hyrox.
- **Soruyla kapatır:** `What would you say?` (464 reply aldı).
- **Kapanış kalıpları:**
  - `PS.` ile ek espri.
  - İmza: `Godspeed 🫡`, `See you on November 16, builders 🏴‍☠️🫡`.
- **Emojiler:**
  - Madde işareti olarak: ⭐️ 📈 🏴‍☠️ 📧
  - Kapanışta: ❤️ 🫡 🤗 😁
  - Başlığı sarmak için: `✨ I rebuilt my personal website ✨`
- **Aforizma:** `You can't lose in entrepreneurship.` / `You either win, or you learn.` (3.4K)
- **Reply'ları:**
  - Sıcak ve samimi: `Yes sir!`, `Welcome on board captain`, `let's goooo!!!`, `i love u too man <3`
  - %21'i küçük harfle başlıyor.
  - Eleştiriye sakin ve uzun bir bağlam açıklamasıyla cevap verir: `This tweet lacks context ...`

---

## 4. Bu örneklemde en çok etkileşim alan kalıplar

| Kalıp | Örnek | Beğeni |
|---|---|---|
| Gündem + meme quote | levelsio `ChatGPT in Germany in 2027` | 24.8K |
| Claude Code ile çılgın demo videosu | levelsio GTA San Andreas görevi | 22.4K |
| Uzun kişisel hikaye | levelsio São Paulo'daki Uber şoförü | 12.5K |
| Zıtlık aforizması | levelsio `never been this easy ... never this hard` | 9.9K |
| Kısa hot take | marclou `the end of UI for SaaS` | 4.8K |
| Kalem kalem maliyet şeffaflığı | levelsio `💸 biz expenses ~$300/mo` | 4.8K |
| Ders aforizması | marclou `You either win, or you learn.` | 3.4K |
| Gelir raporu | marclou `I made $107,142 in October 2026` | 2.3K, 844K görüntülenme |
| İtiraf ve düzeltme | marclou `I made a mistake.` | 1.5K |
| Topluluğa soru | marclou `$2.5M offer ... What would you say?` | 1.1K, 464 reply |

levelsio'nun en yüksek etkileşimli tweetlerinin bir kısmı siyasi ve kutuplaştırıcı (Avrupa, göç, refah devleti). Bunlar senin markan için risk.

---

## 5. Senin sesin (@mrtkrgzgl): şu anki durum

Son 20 tweetine bakarak:

- **Dil:** Çoğu İngilizce. Türk kitlesine yönelik olanlar Türkçe (`Kral hareket!`).
- **Format:** Zaten kısa satırlar ve boş satırlarla yazıyorsun, hashtag kullanmıyorsun. Athens tweeti neredeyse birebir levelsio formatında:
  - yemek → €80 → uyudum → `€480+ in sales` → `This is why you build products on the internet`
- **Hangi tweet tutuyor:** Kişisel hikayeler analiz ve link tweetlerinden daha çok görüntülenmiş. Örneklem küçük ama levelsio ve marclou'nun mantığıyla örtüşüyor: üçüncü şahıs analiz, birinci şahıs deneyimin gerisinde kalıyor.
  - Athens: 188 görüntülenme. Acropolis: 175.
  - Postiz serisi: 37-68.
- **Malzeme:**
  - Ürünler: Ravenpost (Postiz rakibi, %40 affiliate), TraderSpy, FootVal, Sanji.
  - MCP sunucuları; AndonCord ve claude-code-usage-bar.
  - İstanbul, eşinle seyahat, Claude ile hızlı ürün çıkarma.
- **Hesap:** Blue verified olduğu için 280 karakteri aşan tweet atabiliyorsun.

---

## 6. Üretim kuralları

1. **Konuyu sen verirsin.** Her konu için 3 varyant yazarım:
   - (a) levelsio tonu
   - (b) marclou tonu
   - (c) kısa one-liner veya aforizma
   Uygunsa bir reply versiyonu da eklerim.
2. **Dil:** Varsayılan İngilizce. İstersen Türkçe yazarım.
3. **Rakam uydurmam.** Gerçek rakamı vermediğin yere `[X]` gibi bir boşluk bırakırım.
4. **Hashtag yok.** Link sadece istersen ve tercihen ilk reply'da.
5. **İlk satır tek başına okunduğunda merak uyandırmalı.**
6. **Ürün adı geçiyorsa hikayenin içinde geçer,** satış cümlesi kurmam.
   - **Başkalarının tweetlerine atılan reply'larda ürün adı hiç geçmez.** Ürün yalnızca kendi tweetlerinde ya da konu zaten sen veya ürünün olduğunda geçer.
   - **İstisna:** Biri doğrudan senin kategorindeki araçları soruyorsa ürün en sonda, "Full disclosure" notuyla geçebilir. Önce tarafsız bir cevap verilir.
7. **Siyasi ve kutuplaştırıcı konulara** sen açıkça istemedikçe girmem.
8. **Varsayılan tür tespit:** gözlem, fikir, rakamlı analiz ya da espri. Ürün tweetini sadece sen istediğinde yazarım, o zaman da hikaye, rakam ya da espri içinde.

---

## 7. Reply stratejisi: nereye reply atıyorlar

Her hesabın son 20 reply'ının ana tweetlerine bakıldı (13 Kasım 2026).

| | Kendi tweetinin altında | Başkasının tweetinde |
|---|---|---|
| levelsio | 9 (1 reply'ın ana tweeti silinmiş) | 10 reply, 6 farklı thread |
| marclou | 14 | 6 |

**Kendi tweetlerinin altında:** Gelen soruları tek tek cevaplıyorlar (hackathon kuralları, Interior AI özellikleri). Kısa, bilgi veren, sıcak cevaplar. marclou'nun en çok beğenilen reply'ı kendi viral tweetinin altına yazdığı uzun bir devam metni (182 beğeni, 33K görüntülenme).

**Başkalarının tweetlerinde:**
- **Hesap büyüklüğü:** Reply attıkları hesapların neredeyse hepsi 600 ile 15K takipçi arasında. Tek istisna 132K takipçili @catalinmpit. Orada marclou kendisi hakkındaki bir iddiaya bağlam ekliyor.
- **levelsio kendi deneyimi olan konulara giriyor:**
  - Hollanda ekonomisi: Hollandaca tek satır, 104 beğeni.
  - Lizbon'daki bir restoran: içeriden bilgiyle espri, 44 beğeni.
  - Hava temizleyici: kendi cihazının fotoğrafıyla tavsiye.
  - Bir prototip: `Very cool`.
- **marclou kendisinden ya da ürünlerinden bahsedenlere cevap veriyor:**
  - Hackathon katılımcısı: `Hoy hoy`.
  - Övgü tweeti: ortak anıyla teşekkür.
  - TrustMRR destek şikayeti: `pushing a fix!`
  - Eleştiri: sakin bir bağlam açıklaması.
  - Arkadaşının başarısı: Typefully'nin satışını kutluyor.
- **En çok tutan dış reply:** içeriden bilgiye dayanan, tek satırlık bir espri.
- **Dış reply'larda ürün neredeyse hiç geçmiyor:** 16 reply'ın sadece 2'sinde ürün adı var. İkisinde de konu zaten kendileriydi: biri eleştiriye cevap, diğeri sohbetin içinde anlatılan bir anı.
  - Reply'ın işi ilginç olmak. Profiline tıklayan, ürünleri bio'da ve kendi tweetlerinde görür.

**AI reply uyarısı:** levelsio AI reply'lardan nefret ediyor.
- Bir thread'de `AI bot you just replied to fyi` diye yazmış.
- `X should have a zero tolerance policy for AI replies` tweeti 4.8K beğeni almış.
- Reply'lar kısa, spesifik ve kişisel deneyime dayalı olmalı. `Great insight! 🚀` gibi genel cümleler yasak.

**@mrtkrgzgl için uyarlama (1.1K takipçi):**
1. Kendi tweetlerine gelen her yoruma cevap ver.
2. Dış reply'ları nişindeki 1K ile 20K takipçili hesaplara at. Çok büyük hesaplara sadece ilk dakikalarda ve gerçekten özgün bir şey varsa yaz.
3. Sadece gerçek deneyimin olan konulara gir. Ürün adını değil, deneyimini paylaş:
   - Sosyal medya planlama: Ravenpost, Postiz, Typefully, Buffer.
   - Kripto trading verisi: TraderSpy.
   - Futbol verisi: FootVal.
   - Claude Code ve MCP.
   - İstanbul, Türkiye; kışın sıcak bir yerden çalışmak.
4. Nişindeki satışları ve milestone'ları kutla.
5. Seni ya da ürünlerini anan herkese cevap ver, destek sorularına da açık açık.
