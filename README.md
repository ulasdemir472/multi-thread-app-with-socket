# Web İstemci ve Sunucu Uygulaması 🌐

Bu proje, Flask kullanarak geliştirdiğimiz basit bir web istemci ve sunucu uygulamasını içerir. Uygulama, istemci ve sunucu arasında dinamik, çoklu bağlantıları destekleyen bir ağ uygulamasını sağlar.

🚀 Başlangıç

Projeyi yerel makinenize klonlayarak başlayın:

```bash
git clone https://github.com/ulasdemir472/multi-thread-app-with-socket.git
cd proje
```

🏗️ Proje Yapısı
Proje, aşağıdaki ana dosyalardan oluşur:

app.py: Flask tabanlı web sunucusunu ve Socket.IO'yu başlatır.
index.html: Temel HTML dosyası, istemci ve sunucu arasındaki iletişimi sağlar.
server.py: Socket.IO sunucu tarafı, istemciden gelen mesajları dinler.
client.py: Socket.IO istemci tarafı, sunucuya mesaj gönderir.

🚦 Çalıştırma
Flask uygulamasını başlatın:
```bash
python app.py
```
Tarayıcınızda http://127.0.0.1:5000 adresine gidin.

Web sayfasındaki "Server" ve "Client" panelleri arasında etkileşim sağlayın.

NOT: Döviz API bilgileri ```https://fixer.io/``` sitesinden çekilmiştir.
