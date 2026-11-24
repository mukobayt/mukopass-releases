# MukoPass

**Serbest internet • by Dev. MUKO**

Bir siteye girmek istediğinizde "Bu siteye erişim engellenmiştir" sayfasıyla mı karşılaşıyorsunuz? MukoPass, internet sağlayıcısının uyguladığı erişim engellerini **tek bir düğmeyle** aşmanızı sağlayan ücretsiz ve reklamsız bir Windows uygulamasıdır. Açın, büyük düğmeye basın, sitelere her zamanki gibi girin. Bu kadar.

### ⬇️ [MukoPass'i indir (MukoPass-Setup.exe)](https://github.com/mukobayt/mukopass-releases/releases/latest/download/MukoPass-Setup.exe)

Ücretsizdir. Reklam, üyelik ya da abonelik yoktur.

---

## MukoPass bir VPN değildir, daha iyisidir

VPN'ler internet trafiğinizi başka bir ülkedeki, başkasına ait bir sunucunun üzerinden geçirir. Bu hem bağlantınızı yavaşlatır hem de bütün trafiğinizi o sunucunun sahibine emanet etmeniz anlamına gelir.

MukoPass böyle çalışmaz:

- **Trafiğiniz hiçbir uzak sunucuya gitmez.** Her şey kendi bilgisayarınızın içinde işlenir.
- **Hızınız düşmez.** Arada ek bir sunucu olmadığı için internetiniz her zamanki hızındadır.
- **Konumunuz değişmez.** Siteler sizi yine Türkiye'den bağlanıyor olarak görür; bankacılık, e-Devlet ve yerel uygulamalar sorunsuz çalışmaya devam eder.
- **Hesap, giriş, kota yok.** Kimseye e-posta ya da kişisel bilgi vermezsiniz.

## Nasıl çalışır?

İnternet sağlayıcıları bir siteyi engellerken, siz o siteye bağlanırken giden ilk paketin içindeki site adına bakar. MukoPass bu ilk paketi, site adı okunamayacak şekilde düzenler. Site ile aranızdaki bağlantı ise her zamanki gibi şifreli ve güvenli kalır. Ayrıca alan adlarını **şifreli DNS (DoH)** ile çözerek DNS tabanlı engelleri de aşar.

MukoPass dört mod sunar:

| Mod | Ne yapar? |
|---|---|
| **Otomatik** (önerilen) | Bağlantınızı kendisi dener ve sizin için en iyi çalışan modu seçer. |
| **Standart** | Siteye giden ilk paketi, site adı okunamayacak şekilde parçalara böler. |
| **Güçlü** | Parçaların sırasını da değiştirir; daha sıkı engellerde işe yarar. |
| **Alternatif** | Diğer modların yetmediği bağlantılar için farklı bir yöntem. |

Hangisini seçeceğinizi düşünmenize gerek yok: **Otomatik** mod bunu sizin yerinize yapar.

## Kullanımı çocuk oyuncağı

- **Tek düğme:** Ortadaki büyük düğmeye basın; yeşil yandığında hazırsınız.
- **Arka planda çalışır:** Pencereyi kapatınca MukoPass saatin yanındaki simgede çalışmaya devam eder. Simgeden açıp kapatabilirsiniz.
- **İz bırakmaz:** MukoPass'i kapattığınızda internet ayarlarınız eski haline döner; bilgisayarınızda kalıcı bir değişiklik yapılmaz.
- **28 dil:** Türkçe başta olmak üzere 28 dilde arayüz.
- **Hep güncel:** Yeni sürüm çıktığında MukoPass size haber verir ve tek tıkla güncellenir. Her güncelleme kurulmadan önce **SHA-256 ile doğrulanır**; bozuk ya da değiştirilmiş bir dosya asla kurulmaz.

## Güvenilir mi?

- **Reklam, gizli yazılım ya da araç çubuğu yok.** Kurulum yalnızca MukoPass'i kurar.
- **Verileriniz sizde kalır:** Trafiğiniz hiçbir aracı sunucuya yönlendirilmez; MukoPass yalnızca sizin bilgisayarınızda çalışır.
- **Şeffaf:** Kullandığı açık kaynak bileşenlerin lisansları programın "Hakkında" bölümünde listelenir.
- **İstediğiniz an kaldırın:** Windows'un "Uygulamalar" bölümünden tek tıkla tamamen kaldırılır.

## Kurulum

1. Yukarıdaki bağlantıdan `MukoPass-Setup.exe` dosyasını indirin.
2. Çalıştırın ve **Kur**'a basın.
3. MukoPass açılınca ortadaki düğmeye basın. Hepsi bu.

**Gereksinimler:** Windows 10 veya 11 (32 ya da 64 bit).

## Kullanım şartları

Ayrıntılar: [Kullanım Sözleşmesi / License Agreement](EULA.md). MukoPass ücretsizdir; kaynak kodu açık değildir. Kurulum dosyasını değiştirmeden paylaşabilirsiniz. Programın kullanımından doğan sorumluluk kullanıcıya aittir; lütfen bulunduğunuz yerin yasalarına uygun şekilde kullanın.

---

# MukoPass

**Free internet • by Dev. MUKO**

MukoPass is a free, ad-free Windows app that gets you past ISP-level website blocking with a single button.

### ⬇️ [Download MukoPass (MukoPass-Setup.exe)](https://github.com/mukobayt/mukopass-releases/releases/latest/download/MukoPass-Setup.exe)

- **Not a VPN:** your traffic never goes through a remote server; everything is processed on your own computer, so your speed and location stay the same.
- **How it works:** it reshapes the first packet of each connection so the site name can't be read by blocking filters, and resolves domains over encrypted DNS (DoH). Your connection to the site stays encrypted as usual.
- **Four modes:** Automatic (recommended, picks the best method for your connection), Standard, Strong and Alternative.
- **One button,** runs in the system tray, restores your network settings when closed, available in 28 languages.
- **Safe updates:** MukoPass tells you when a new version is out and verifies each update with SHA-256 before installing.
- **No ads, no bundled software, no account required.**

Please use MukoPass in accordance with the laws where you live. See the [License Agreement](EULA.md).
