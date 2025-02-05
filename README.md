# DevastatingInsight: Debian Tabanlı OSINT, SOCMINT ve WEBINT Dağıtımı

**DevastatingInsight**, OSINT (Açık Kaynak İstihbarat), SOCMINT (Sosyal Medya İstihbaratı) ve WEBINT (Web İstihbaratı) işlemleri için optimize edilmiş bir Debian tabanlı işletim sistemi dağıtımı sunmayı amaçlamaktadır. Dağıtım, bu alanlarda kullanılabilecek en iyi araçları içerir ve özel ihtiyaçlara göre özelleştirilebilir.

## İçindekiler
- [Özellikler](#özellikler)
- [Kurulum](#kurulum)
- [Kullanım](#kullanım)
- [Araçlar](#araçlar)
- [Yapılandırma](#yapılandırma)
- [Güncellemeler ve Bakım](#güncellemeler-ve-bakım)
- [Sıkça Sorulan Sorular (SSS)](#sıkça-sorulan-sorular-sss)
- [Katkıda Bulunma](#katkıda-bulunma)
- [Lisans](#lisans)

## Özellikler
- **OSINT Araçları:** Gelişmiş açık kaynak istihbarat araçlarıyla donatılmıştır.
- **SOCMINT Araçları:** Sosyal medya platformlarından veri toplama ve analiz etme yetenekleri.
- **WEBINT Araçları:** Web tabanlı veri toplama ve analiz araçları.
- **Grafiksel Arayüz:** Kullanımı kolay ve kullanıcı dostu grafiksel arayüz.
- **Modüler Yapı:** Yüksek özelleştirme imkanı sunar, kullanıcıların ihtiyaçlarına göre modüller eklenebilir veya çıkarılabilir.
- **Güvenlik ve Performans:** Dağıtım, güvenlik ve performans açısından optimize edilmiştir.
- **Otomatik Güncellemeler:** Düzenli olarak otomatik güncellemelerle sistemin güncel ve güvenli kalması sağlanır.
- **Kapsamlı Dokümantasyon:** Kullanıcıların araçları ve dağıtımı etkili bir şekilde kullanabilmeleri için kapsamlı dokümantasyon.
- **Topluluk Desteği:** Kullanıcılar ve geliştiriciler için bir destek topluluğu.
- **Çoklu Dil Desteği:** Farklı dillerde kullanılabilir.
- **Eğitim ve Öğretim Materyalleri:** Yeni başlayanlar için eğitim ve öğretim materyalleri.

## Araçlar
**DevastatingInsight** dağıtımında yer alan bazı araçlar ve işlevleri:

- **Recon-ng:** Güçlü bir OSINT çerçevesi, modüler yapısı ile veri toplama, analiz ve raporlama yapar.
- **TheHarvester:** E-posta, domain, IP ve isim bilgilerini çeşitli kaynaklardan toplar.
- **Maltego:** Görsel bağlantı ve ilişki analizi yaparak, karmaşık veri kümelerini görselleştirir.
- **SpiderFoot:** OSINT otomasyon aracı, IP adresleri, domainler, e-postalar ve daha fazlası hakkında bilgi toplar.
- **Twint:** Twitter verilerini toplama ve analiz etme aracı, API kullanmadan çalışır.
- **Metasploit Framework:** Pentest ve güvenlik araştırmaları için güçlü bir araç seti sunar.
- **Wireshark:** Ağ trafiği analiz aracı, paket yakalama ve detaylı analiz yapar.
- **John the Ripper:** Parola kırma aracı, zayıf parolaları tespit eder.
- **Hydra:** Parola kırma ve kimlik doğrulama aracı, çeşitli protokoller üzerinde brute force saldırıları yapar.
- **Nmap:** Ağ keşfi ve güvenlik taraması yaparak, açık portları ve hizmetleri tespit eder.
- **SQLmap:** SQL enjeksiyon açıklarını bulma ve kullanma aracı.
- **Burp Suite:** Web uygulama güvenlik testi platformu, çeşitli güvenlik testlerini otomatikleştirir.
- **Nikto:** Web sunucusu güvenlik tarama aracı, bilinen güvenlik açıklarını tespit eder.
- **OpenVAS:** Güvenlik zafiyeti tarama aracı, ağ güvenliği değerlendirmesi yapar.
- **ExifTool:** Medya dosyalarının meta verilerini okuma, yazma ve düzenleme aracı.
- **OSINT Framework:** Farklı OSINT kaynaklarına erişim sağlayan web tabanlı bir araç.
- **Censys:** İnternet varlıklarının keşfi ve analizi için kullanılan bir arama motoru aracı.
- **Shodan:** İnternete bağlı cihazların keşfi ve analizi için kullanılan bir arama motoru.
- **FOCA:** Belge meta verilerini analiz ederek, bilgi toplama işlemlerine yardımcı olur.
- **SpiderFoot HX:** Daha gelişmiş özelliklere sahip bir OSINT otomasyon aracı.
- **Sublist3r:** Alt domainleri toplama aracı, çeşitli kaynaklardan alt domainleri tespit eder.
- **Amass:** DNS keşfi ve dış istihbarat toplama aracı.
- **Social-Engineer Toolkit (SET):** Sosyal mühendislik saldırılarını simüle etme aracı.
- **Cuckoo Sandbox:** Zararlı yazılım analiz ortamı, şüpheli dosyaları ve URL'leri analiz eder.
- **Yara:** Zararlı yazılım tespiti ve analizinde kullanılan bir araç.
- **Radare2:** Tersine mühendislik aracı, binary dosyalarını analiz eder.
- **Ghidra:** NSA tarafından geliştirilen bir tersine mühendislik aracı.
- **Aircrack-ng:** Kablosuz ağlar için güvenlik değerlendirme araçları seti.


## Kurulum
Aşağıdaki adımları izleyerek **DevastatingInsight** dağıtımını kurabilirsiniz:

1. **Gereksinimler:**
    - En az 4 GB RAM
    - 20 GB boş disk alanı
    - Debian tabanlı bir işletim sistemi

2. **Yükleme Adımları:**
    ```bash
    git clone https://github.com/n5k5i5/DevastatingInsight.git
    cd DevastatingInsight
    sudo ./install.sh
    ```

## Kullanım
Kurulum tamamlandıktan sonra, aşağıdaki komutları kullanarak dağıtımı başlatabilirsiniz:

```bash
osint-start
