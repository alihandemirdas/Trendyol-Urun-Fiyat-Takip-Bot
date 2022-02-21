# Trendyol-Urun-Fiyat-Takip-Bot
[TR] 
Bu bot ile, Trendyol'daki fiyatlarını takip etmek istediğiniz ürünleri, linklerini links.txt dosyasına ekleyerek toplu bir şekilde 10 dakika aralıklarla kontrol edebilirsiniz. Uzak sunucuda sürekli çalışması gerekir.
Eğer ürünün fiyatı düşerse, Telegram üzerinden oluşturduğunuz bot aracılığıyla, yine Telegram üzerinden oluşturduğunuz gruba anlık olarak bildirim gönderir.

Bunun için Telegram uygulamasına girip @BotFather kullanıcı adını aratıyoruz. Karşımıza çıkan verified bot aracığıyla ismini ve kullanıcı adını bizim belirlediğimiz yeni bir bot oluşturuyoruz.
Bot oluşunca size bot token bilgisi verecek bunu kaydediyoruz. bot.py dosyasında dosyasında gerekli yere yapıştırıyoruz.
https://api.telegram.org/bot<tokeniburayayapistir>/getUpdates bu adrese gidiyoruz, tokeni linke eklemeyi unutmayın, ekledikten sonra <> bu karakterleri kaldırabilirsiniz. 
Chat id'mizi çıkan sayfadan kopyalıyoruz ve yine bot.py dosyasında gerekli yere yapıştırıyoruz.
Daha sonra yeni bir grup oluşturup, bu yeni oluşturduğumuz botu bu gruba ekliyoruz.

Gerekli Kütüphaneler:
- BeautifulSoup4
- Requests

Windows cihazınızda python yüklü ise, komut satırını açıp "pip install beautifulsoup4" ve "pip install requests" şeklinde kurulumunu yapabilirsiniz.

[EN] 
With this bot, you can check the products whose prices you want to follow on Trendyol, by adding their links to the links.txt file, at 10-minute intervals. It should run continuously on the remote server.
If decrease the price of products, it will send instant notification to the group you have created via Telegram, via the bot you created on Telegram.

For this, we enter the Telegram application and search for the @BotFather username. We are creating a new bot, whose name and username we specify, through the verified bot that appears.
When the bot is created, it will give you bot token information and we save it. Paste it in the required place in the bot.py file.
https://api.telegram.org/bot<tokeniburayayapistir>/getUpdates we go to this address, don't forget to add the token to the link, after adding <> you can remove these characters.
We copy our chat id from the page and paste it to the required place in the bot.py file.
Then we create a new group and add this newly created bot to this group.

Required Libraries:
- BeautifulSoup4
- Requests

If you have python installed on your Windows device, you can open the command line and install it as "pip install beautifulsoup4" and "pip install requests".
