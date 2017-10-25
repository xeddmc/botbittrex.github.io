# BotBittrex'in GitHub Websitesine Hoşgeldiniz

### [Click here](README.md) to continue in English.<br>
### BotBittrex Nedir?
BotBittrex, kripto para birimleri için yazılmış PHP ve RSS tabanlı birçok bölümden oluşan bir Bilgilendirme/ALIŞ-SATIŞ botudur. BotBittrex, kendi algoritması aracılığıyla fiyatının yükselme ihtimali olan altcoinlerden sizi haberdar edebilir, bu altcoinlerden sizin adınıza Bittrex Borsası üzerinden otomatik ALIŞ/SATIŞ yapabilir, yine Bittrex Borsası üzerinden ALIŞ/SATIŞ emirlerinizin gerçekleşmesi durumunda Telegram yoluyla (ya da email ile) size bilgi mesajı gönderebilir ya da almış olduğunuz bir altcoinden kara geçmeye başladığınızda yine Telegram üzerinden (ya da email ile) size bilgilendirme mesajı gönderen ve farklı abonelik tipleri olan bir servistir.

Telegram'da bulunan birçok sinyal grubunun aksine BotBittrex size **ASLA** ALIŞ/SATIŞ sinyali vermez. Bu kadar volatil bir pazarda size kazandırma sözü veren kişi ya da gruplara itibar etmemenizi tavsiye ederiz. **BALİNA** diye tabir edilen bazı grupların sizlere ellerinde kalan altcoinleri aldırmaya çalıştığını ve işin içine insan girdiğinde hertürlü manipülasyona açık bir sistemin oluştuğunu unutmayın. BotBittrex bir yazılımdır. Kendisine öğretilmiş kriterlere göre işlem yapar. Dışardan insan müdehalesi söz konusu değildir. BotBittrex Pro aboneliği hariç tüm verisyonlarında ALIŞ/SATIŞ kararı tamamen size aittir.

### BotBitrex'in abonelik tipleri ve farkları nelerdir?
BotBittrex'in üç farklı abonelik türü bulunmaktadır:
1. BotBittrex Free
2. BotBittrex Lite
3. BotBittrex Pro (Geliştiriliyor)

### BotBittrex Free:
BotBittrex'in [![Twitter Follow](https://img.shields.io/twitter/follow/botbittrex.svg?style=social&label=Follow)](http://twitter.com/botbittrex) hesabını takip ederek, algoritmasının belirlediği altcoinlerden ücretsiz olarak her üç saatte bir haberdar olabilirsiniz. Her üç saatte bir 0-5 adet seçilmiş altcoinin mevcut fiyat bilgisini **(Price)**, son bir saat içindeki değişimini **(1H)**, son 24 saat içindeki değişimini **(24H)** ve son bir hafta içersindeki değişimini **(7D)** görebilirsiniz. **Unutmayın BOTun önerdiği altcoinlerin size para kazandırma garantisi yoktur. Seçtiği altcoinlere yatırım yapmak kullanıcının sorumluluğundadır.** Derin bir teknik analiz yapmadan sadece belli kriterlere sahip (Hacim, Pazar Payı, Değişim vs.) altcoinleri seçerek size sunar. Binlerce altcoinin olduğu bu pazarda bu incelemeyi biz insanların tek tek altcoinlere bakarak yapması çok uzun zaman alırken, BOT bunu saniyeler içersinde yapmaktadır. BotBittrex, proof tipi **PoS (Proof of Stake)** olan altcoinleri **SEÇMEZ.**

![Twitter](twitter.png)

BotBittrex Free hizmetinden yararlanmak için lütfen [![Twitter Follow](https://img.shields.io/twitter/follow/botbittrex.svg?style=social&label=Follow)](http://twitter.com/botbittrex) takip ediniz.

### BotBittrex Lite:
BotBittrex Lite, Bittrex API kullanarak mevcut emirlerinizin durumunu 15 dakikada bir kontrol eder ve açık emirlerinizin gerçekleşmesi durumunda aşağıdakine benzer Telegram mesajları (ya da email) gönderir.

![Orders](Telegram_iOS.png)

Buna ek olarak elinizdeki altcoinlerin son fiyat bilgilerini 15 dakikada bir kontrol ederek, kara geçtiğinizde size Telegram (ya da email) ile bilgilendirme mesajları gönderir.

![Profit](Telegram_profit.png)

BotBittrex Free, size üç saatte bir twitter hesabımız [![Twitter Follow](https://img.shields.io/twitter/follow/botbittrex.svg?style=social&label=Follow)](http://twitter.com/botbittrex) üzerinden altcoin önerirken, BotBittrex Lite ile Telegram kanalımıza katılarak 15 dakikada bir algoritmanın önerdiği altcoinlerden haberdar olabilirsiniz.

![Signal](Telegram_signal.png)

### BotBittrex Lite'a nasıl üye olabilirim ve neler gereklidir?

BotBittrex Lite aylık abonelikle yaralanabileceğiniz bir servis olup, aylık **0.01 BTC** ücret karşılığında bu servisten yararlanabilirsiniz. Ödemeniz ulaşır ulaşmaz aboneliğiniz başlar ve aboneliğiniz yenilenmediği takdirde 30 gün sonra sistem tarafından aboneliğiniz iptal edilir. Ödemenizi aşağıdaki adrese gönderdikten sonra TX bilgisini twitterdan bize ulaştırmanızı istiyoruz.<br>

## BTC:
## 1LaZG8XELxs9JCzzVJaWyhxQG6tCcswJnx

![BTC Address](btc_address.png)

BotBittrex Lite hizmeti size karlılık ve son 10 ALIŞ/SATIŞ emrinizin gerçekleşmesi bilgilerini içeren bir RSS feed hizmeti sunar. ücretsiz IFTTT.com servisini kullanarak Telegram, Email, Twitter, Facebook vb üzerinden bildirim alabilirsiniz. Lite üyelikte size özel bir URL vereceğiz. O adres sizin 15 dakikada bir güncellenen RSS Feed adresiniz olacak. Herhangi bir hosting, teknik bilgi-beceri gerektirmiyor. Ücretsiz bir IFTTT.com üyeliği yeterli olacaktır. Yaygın olarak **RSS->IFTTT.com->Telegram** dönüşümü kullanılmaktadır.

Bittrex Borsasına üye değilseniz burayada üye olmanız gerekiyor. Bittrex için bu BOT yazıldı. Bittrex üyeliğiniz olduktan sonra 2FA'yı açıp (iki aşamalı güvenlik) API bölümünden aşağıdaki şekilde görüldüğü gibi bir API key oluşturup o keye **SADECE READ INFO** izni verip, key ve secretı [![Twitter URL](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](http://twitter.com/botbittrex) üzerinden DM ile ulaştırmanız gerekmektedir. Sadece **READ INFO** izni Lite abonelik için yeterli olup, ne bize ne de başkasına kesinlikle **WITHDRAW** izni vermeyiniz! **WITHDRAW** izni verdiğiniz API kullanıcıları tüm paranızı çekebilir. Bu yüzden kimseye **WITHDRAW** izni vermeyiniz.

![API Read](API_read.png)

Size ulaşabilmemiz için geçerli bir email adresinizin olması gerekiyor. Yine üyelerimize özel Telegram grubumuza katılmak içinde Telegram kullanıcısı olmanız gerekiyor. Kısa bir süreliğine 7 günlük BotBittrex Lite hizmetimizden yararlanmak için bize twitterdan ulaşabilirsiniz.


You can use the [editor on GitHub](https://github.com/botbittrex/botbittrex.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/botbittrex/botbittrex.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
