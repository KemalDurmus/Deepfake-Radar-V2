# Deepfake-Radar
C# ve Python ile geliştirilmiş, derin öğrenme tabanlı Deepfake Ses Tespit ve Savunma Sistemi.
# 🛡️ Deepfake Audio Radar & Defense System

Gelişmiş Derin Öğrenme (Deep Learning) algoritmaları kullanarak, mikrofon veya dosya üzerinden gelen sesin gerçek bir insana mı yoksa yapay zekaya (Deepfake) mı ait olduğunu tespit eden çift motorlu siber güvenlik aracı.

## 🚀 Öne Çıkan Özellikler
* **Çift Motorlu Mimari:** Kullanıcı arayüzü ve sistem kontrolü **C# (.NET)** ile, yapay zeka ve ses analiz motoru ise **Python** ile geliştirilmiştir. İki dil arası kesintisiz haberleşme sağlanır.
* **Hayalet Modu (Stealth Mode):** Operasyonel gizlilik için program görev çubuğunda (Taskbar) iz bırakmaz. Küçültüldüğünde kendini sağ alt köşeye (System Tray) özel bir kalkan ikonuyla gizler.
* **Yapay Zeka Destekli Analiz:** Eğitilmiş özel `.h5` derin öğrenme modeli (Keras/TensorFlow) kullanılarak yüksek doğruluk oranına sahip ses tespiti yapılır.
* **Siber Zırh (Obfuscation):** Kötü niyetli tersine mühendislik (Reverse Engineering) saldırılarına karşı C# çekirdek kodları şifrelenerek (Spagetti Kod) korunmaya alınmıştır.

## 🛠️ Kurulum ve Kullanım
Proje bağımsız (portable) çalışacak şekilde tasarlanmıştır, ekstra bir kurulum gerektirmez.

1. Sağ taraftaki **Releases** bölümünden son sürümü (`.zip`) indirin ve bir klasöre çıkartın.
2. Önce arka plan yapay zeka motorunu ayağa kaldırmak için **`api.exe`** dosyasını çalıştırın.
3. Sunucu aktif olduktan sonra ana radar arayüzü olan **`deepfake.exe`**'yi çalıştırın.
4. Sistemi gizlemek için sağ üstteki eksi (-) butonuna basın. Geri çağırmak için sağ alttaki kalkan ikonuna çift tıklayın.

## ⚠️ Güvenlik Notu
*Bu projenin ana yürütülebilir dosyası (`deepfake.exe`), izinsiz kopyalamayı ve kaynak kod analizini engellemek amacıyla **ConfuserEx** kullanılarak zırhlanmıştır.*
