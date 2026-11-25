# Tiltverse — Gizlilik Politikası

**Yürürlük tarihi:** 24 Kasım 2026 (Android sürümü eklendi)
**Uygulama:** Tiltverse (iOS ve Android)
**Geliştirici:** Vedat Ermiş
**İletişim:** vedatermis@hotmail.com

---

## Kısaca

Tiltverse'te hesap açmanız gerekmez. Adınızı, e-postanızı, telefon numaranızı veya konumunuzu **istemiyoruz ve toplamıyoruz**. Geliştirici olarak bizim işlettiğimiz hiçbir sunucu yoktur; oyun ilerlemeniz telefonunuzda kalır.

Yalnızca iki yerde veri, bizim dışımızdaki şirketlere gider:

1. **Reklamlar** — Unity Ads reklam gösterebilmek için cihazınıza ait teknik bilgileri işler.
2. **Skor tabloları (yalnızca iOS)** — Game Center'a giriş yaptıysanız, oyun içi toplam puanlarınız Apple'a gönderilir.

Ayrıntılar aşağıda.

---

## 1. Hangi veriler işleniyor

### 1.1. Bizim doğrudan topladığımız veriler

**Hiçbiri.** Tiltverse'in geliştirici tarafından işletilen bir sunucusu, veritabanı veya analiz sistemi yoktur. Oyunu oynarken bize hiçbir veri ulaşmaz.

### 1.2. Cihazınızda kalan veriler

Aşağıdakiler telefonunuzun yerel deposunda (iOS'ta `UserDefaults`, Android'de `SharedPreferences`) tutulur ve **cihazdan hiçbir yere gönderilmez**:

- Tamamlanan bölümler ve açılan kilitler
- Her bölüm için en iyi süre, toplanan küre sayısı ve madalya
- Ses, titreşim, eğim hassasiyeti gibi ayarlar
- Hikâye bölümlerini görüp görmediğiniz

Uygulamayı sildiğinizde bu veriler de silinir.

### 1.3. Hareket sensörü

Oyun, topu yönlendirmek için telefonunuzun ivmeölçer ve jiroskop verilerini okur. Bu veriler **yalnızca o anki oyun oturumu içinde**, topun hareketini hesaplamak için kullanılır. Kaydedilmez, saklanmaz, hiçbir yere gönderilmez.

### 1.4. Game Center (isteğe bağlı, yalnızca iOS)

Android sürümünde skor tablosu yoktur; Google Play Games kullanılmaz ve bu bölümdeki veriler Android'de hiç işlenmez.


Cihazınızda Game Center'a giriş yapmışsanız, oyun Apple'ın skor tablolarına üç toplam değer gönderir:

- Tamamlanan bölüm sayısı
- Toplanan toplam küre sayısı
- Kazanılan altın madalya sayısı

Bu veriler Apple tarafından, Apple'ın gizlilik politikası kapsamında işlenir. Oyunculara Game Center'da görünen takma adınızı Apple belirler; biz Apple Kimliğinizi, e-postanızı veya gerçek adınızı **görmeyiz**.

Game Center'ı kullanmak zorunda değilsiniz. Giriş yapmazsanız oyun eksiksiz çalışır, yalnızca skor tablosu özelliği devre dışı kalır.

Apple'ın gizlilik politikası: https://www.apple.com/legal/privacy/

### 1.5. Reklamlar — Unity Ads

Tiltverse ücretsizdir ve **Unity Ads** üzerinden reklam gösterir:

- **Geçiş reklamı:** bölüm tamamlandıktan sonra, belirli aralıklarla
- **Ödüllü reklam:** yalnızca siz isterseniz — canlarınız bittiğinde devam etmek için

Reklam gösterebilmek için Unity Technologies aşağıdaki türde verileri işleyebilir:

- Cihaz tanımlayıcıları — iOS'ta IDFV (satıcıya özel tanımlayıcı), Android'de Android reklam kimliği (AAID)
- Cihaz modeli, işletim sistemi sürümü, dil ve ülke ayarı
- IP adresi ve ondan çıkarılan yaklaşık konum (ülke/şehir düzeyi; hassas konum alınmaz)
- Uygulama kullanım süreleri ve teknik teşhis verileri
- Reklamla etkileşiminiz (gösterildi mi, izlendi mi, tıklandı mı)

Bu verileri **biz görmüyoruz**; doğrudan Unity'nin sistemlerine gider.

**Reklamlar kişiselleştirilmez.** Oyun, Unity Ads'i her başlattığında Unity'ye davranışsal (ilgi alanına dayalı) hedefleme yapmamasını bildirir; Avrupa Birliği ve ABD eyalet yasaları kapsamında da "izin yok / paylaşım yok" olarak işaretlenir. Unity bu verileri yine de reklamı gösterebilmek, gösterim sıklığını sınırlamak ve dolandırıcılığı önlemek için kullanır.

Android'de reklam kimliğinizi istediğiniz zaman **Ayarlar > Gizlilik > Reklamlar** (bazı cihazlarda **Ayarlar > Google > Reklamlar**) bölümünden sıfırlayabilir veya silebilirsiniz.

Unity'nin oyuncular için gizlilik politikası:
https://unity.com/legal/game-player-and-app-user-privacy-policy

### 1.6. SKAdNetwork (yalnızca iOS)

Uygulama, Apple'ın **SKAdNetwork** çerçevesini kullanır. Bu çerçeve reklam kampanyalarının başarısını ölçer ama bunu kişi bazında değil, **toplu ve anonim** şekilde yapar. Sizi tanımlayan bir bilgi içermez.

---

## 2. İzleme izni (App Tracking Transparency)

Tiltverse'in bu sürümü **sizden izleme izni istemez** ve Apple'ın reklam tanımlayıcısına (IDFA) **erişmez**.

Bunun pratik anlamı: gördüğünüz reklamlar, başka uygulamalardaki davranışınıza göre kişiselleştirilmez. Bağlamsal reklamlardır.

İleride bu değişirse, uygulama size iOS'un standart izin penceresini gösterecek ve bu politika güncellenecektir. İzin vermemeyi seçmeniz oyunun hiçbir özelliğini kısıtlamaz.

**Android:** Android'de bu tür bir izin penceresi yoktur; Unity Ads, Android reklam kimliğine (yukarıda 1.5) erişebilir. Sonuç iOS ile aynıdır: oyun Unity'ye davranışsal hedefleme yapmamasını bildirir, reklamlar bağlamsaldır. Oyun konum, kamera, mikrofon, kişiler veya depolama izni istemez; izin listesindeki internet, ağ durumu ve reklam kimliği izinleri reklamlar, titreşim izni oyun hissi içindir.

---

## 3. Çocukların gizliliği

Tiltverse 13 yaşın altındaki çocuklara yönelik olarak tasarlanmamıştır ve bilerek 13 yaş altı kullanıcılardan veri toplamayız. Çocuğunuzun verisinin işlendiğini düşünüyorsanız yukarıdaki adresten bize ulaşın.

---

## 4. Veri saklama ve silme

| Veri | Nerede | Nasıl silinir |
|---|---|---|
| Oyun ilerlemesi ve ayarlar | Yalnızca cihazınızda | Uygulamayı silin (Android'de ayrıca Ayarlar > Uygulamalar > Tiltverse > Depolama > Verileri temizle) |
| Game Center skorları (yalnızca iOS) | Apple'ın sunucularında | iOS Ayarlar > Game Center üzerinden yönetin |
| Reklam verileri | Unity Technologies | Unity'nin gizlilik politikasındaki yöntemlerle |

Bizim sakladığımız bir veri olmadığı için, bizden silinmesini isteyeceğiniz bir kayıt da yoktur.

---

## 5. Haklarınız

Bulunduğunuz ülkeye göre — Türkiye'de **KVKK**, Avrupa Birliği'nde **GDPR**, Kaliforniya'da **CCPA** kapsamında — kişisel verilerinize erişme, düzeltilmesini veya silinmesini isteme, işlenmesine itiraz etme haklarına sahipsiniz.

Tiltverse kişisel veri toplamadığı ve saklamadığı için, bu taleplerin çoğu doğrudan veriyi işleyen taraflara yöneltilmelidir:

- **Reklam verileri için:** Unity Technologies — https://unity.com/legal/game-player-and-app-user-privacy-policy
- **Game Center verileri için:** Apple — https://www.apple.com/legal/privacy/

Yine de her türlü soru ve talebiniz için bize yazabilirsiniz: **vedatermis@hotmail.com**

---

## 6. Reklamları kaldırma

Oyun içinde reklamları kapatan bir seçenek sunulursa, bu seçeneği etkinleştirdiğinizde Unity Ads devre dışı kalır ve yukarıda 1.5'te anlatılan veri işleme durur.

---

## 7. Üçüncü taraf bağlantıları

Reklamlar sizi üçüncü taraf web sitelerine, App Store veya Google Play sayfalarına yönlendirebilir. Bu sitelerin içeriğinden ve gizlilik uygulamalarından sorumlu değiliz.

---

## 8. Bu politikadaki değişiklikler

Bu politikayı zaman zaman güncelleyebiliriz. Önemli bir değişiklik olduğunda sayfanın en üstündeki yürürlük tarihi değişir. Uygulamayı kullanmaya devam etmeniz, güncel politikayı kabul ettiğiniz anlamına gelir.

---

## 9. İletişim

Gizlilikle ilgili her konu için:

**Vedat Ermiş**
vedatermis@hotmail.com

---
---

# Tiltverse — Privacy Policy

**Effective date:** 24 November 2026 (Android version added)
**App:** Tiltverse (iOS and Android)
**Developer:** Vedat Ermiş
**Contact:** vedatermis@hotmail.com

---

## In short

Tiltverse does not require an account. We do not ask for and do not collect your name, email address, phone number, or location. We operate no servers as the developer; your game progress stays on your device.

Data leaves your device to third parties in only two cases:

1. **Ads** — Unity Ads processes technical information about your device in order to serve ads.
2. **Leaderboards (iOS only)** — if you are signed in to Game Center, your aggregate scores are sent to Apple.

Details below.

---

## 1. What data is processed

### 1.1. Data we collect directly

**None.** Tiltverse has no developer-operated server, database, or analytics system. Nothing reaches us while you play.

### 1.2. Data that stays on your device

The following is stored in local storage on your phone (`UserDefaults` on iOS, `SharedPreferences` on Android) and is **never transmitted anywhere**:

- Completed levels and unlocked progress
- Best time, orbs collected, and medal earned per level
- Settings such as sound, haptics, and tilt sensitivity
- Whether you have seen the story sequences

Deleting the app deletes this data.

### 1.3. Motion sensors

The game reads your device's accelerometer and gyroscope to steer the ball. This data is used **only within the current play session** to compute ball movement. It is not recorded, stored, or transmitted.

### 1.4. Game Center (optional, iOS only)

The Android version has no leaderboards; Google Play Games is not used and none of the data in this section is processed on Android.


If you are signed in to Game Center, the game submits three aggregate values to Apple's leaderboards:

- Number of levels completed
- Total orbs collected
- Number of gold medals earned

Apple processes this data under Apple's own privacy policy. Your Game Center nickname is determined by Apple; we do **not** see your Apple Account, email address, or real name.

Game Center is optional. If you do not sign in, the game works fully — only the leaderboard feature is unavailable.

Apple's privacy policy: https://www.apple.com/legal/privacy/

### 1.5. Advertising — Unity Ads

Tiltverse is free and shows ads through **Unity Ads**:

- **Interstitial ads:** after completing a level, at spaced intervals
- **Rewarded ads:** only if you choose them — to continue after running out of lives

To serve ads, Unity Technologies may process:

- Device identifiers — IDFV (identifier for vendor) on iOS, the Android advertising ID (AAID) on Android
- Device model, OS version, language and country settings
- IP address and the approximate location derived from it (country/city level; no precise location)
- App usage times and technical diagnostics
- Your interaction with the ad (shown, watched, clicked)

**We do not see this data**; it goes directly to Unity's systems.

**Ads are not personalised.** Every time the game starts Unity Ads, it tells Unity not to use behavioural (interest-based) targeting, and marks the user as "no consent / do not sell or share" under EU and US state privacy laws. Unity still uses this data to deliver the ad, cap how often ads are shown and prevent fraud.

On Android you can reset or delete your advertising ID at any time under **Settings > Privacy > Ads** (on some devices **Settings > Google > Ads**).

Unity's privacy policy for players:
https://unity.com/legal/game-player-and-app-user-privacy-policy

### 1.6. SKAdNetwork (iOS only)

The app uses Apple's **SKAdNetwork** framework. It measures advertising campaign performance in an **aggregated and anonymous** way, not at the individual level, and contains no information identifying you.

---

## 2. App Tracking Transparency

This version of Tiltverse **does not ask for tracking permission** and **does not access** Apple's advertising identifier (IDFA).

In practice this means the ads you see are not personalised based on your behaviour in other apps. They are contextual ads.

If this changes in a future version, the app will show the standard iOS permission prompt and this policy will be updated. Declining will not restrict any feature of the game.

**Android:** Android has no equivalent permission prompt; Unity Ads may access the Android advertising ID (see 1.5). The result is the same as on iOS: the game tells Unity not to use behavioural targeting, and ads are contextual. The game does not request location, camera, microphone, contacts or storage permissions; the internet, network state and advertising ID permissions in its permission list are for ads, and the vibration permission is for haptic feedback.

---

## 3. Children's privacy

Tiltverse is not directed at children under 13, and we do not knowingly collect data from users under 13. If you believe your child's data has been processed, please contact us at the address above.

---

## 4. Data retention and deletion

| Data | Where | How to delete |
|---|---|---|
| Game progress and settings | On your device only | Delete the app (on Android also Settings > Apps > Tiltverse > Storage > Clear data) |
| Game Center scores (iOS only) | On Apple's servers | Manage via iOS Settings > Game Center |
| Advertising data | Unity Technologies | Via the methods in Unity's privacy policy |

Because we store no data ourselves, there is no record held by us for you to request deletion of.

---

## 5. Your rights

Depending on where you live — **KVKK** in Türkiye, **GDPR** in the European Union, **CCPA** in California — you have rights to access, correct, or delete your personal data, and to object to its processing.

Since Tiltverse neither collects nor stores personal data, most such requests should be directed to the parties that process the data:

- **For advertising data:** Unity Technologies — https://unity.com/legal/game-player-and-app-user-privacy-policy
- **For Game Center data:** Apple — https://www.apple.com/legal/privacy/

You are welcome to contact us with any question or request: **vedatermis@hotmail.com**

---

## 6. Removing ads

If an option to disable ads is offered in the game, enabling it turns Unity Ads off and the processing described in section 1.5 stops.

---

## 7. Third-party links

Ads may direct you to third-party websites, App Store or Google Play pages. We are not responsible for the content or privacy practices of those sites.

---

## 8. Changes to this policy

We may update this policy from time to time. When a material change is made, the effective date at the top of this page changes. Continued use of the app means you accept the current policy.

---

## 9. Contact

For anything related to privacy:

**Vedat Ermiş**
vedatermis@hotmail.com
