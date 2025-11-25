# Siber Güvenlik & Teknoloji Portfolyosu

Bu repository; sızma testi (pentest) metodolojilerini uyguladığım raporları, çözdüğüm CTF laboratuvarlarını ve modern web/ağ teknolojileri üzerine yaptığım teknik araştırmaları içermektedir. Amacım, teorik bilgiyi pratik uygulamalarla birleştirerek güvenli sistemler inşasına katkıda bulunmaktır.

##  Projeler ve Raporlar

### 1. 🕵 Sızma Testi Raporları (Pentest Reports)

Gerçek dünya senaryoları ve simülasyon ortamlarında tespit edilen zafiyetlerin teknik analizi.

| Dosya Adı | Kategori | Açıklama |
| :--- | :--- | :--- |
| **`Restoran_App_Pentest_Report.pdf`** | Web Security | Yerel bir restoran uygulamasında tespit edilen **Critical** ve **High** seviye zafiyetler. [cite_start]<br>• **Bulgular:** Stored XSS, IDOR (Yetkisiz Silme/Düzenleme), Business Logic Errors (Fiyat Manipülasyonu), Privilege Escalation (Admin Yetkisi Alma). [cite: 619, 648, 677, 743, 855, 983] |

### 2.  CTF & Lab Çözümleri (Write-ups)

Güvenlik açıklarını sömürme ve bayrak yakalama (Capture The Flag) süreçlerim.

| Dosya Adı | Platform | Açıklama |
| :--- | :--- | :--- |
| **`OWASP_Juice_Shop_Writeup.pdf`** | OWASP Juice Shop | Zafiyetli web uygulamasında OWASP Top 10 açıklarının sömürülmesi. [cite_start]<br>• **Senaryolar:** SQL Injection ile Admin girişi, DOM XSS, Hassas Veri İfşası (Backup dosyaları), Broken Access Control (Başkasının sepetini görme). [cite: 1312, 1367, 1447, 1491, 1510, 1523] |

### 3.  Teknik Araştırmalar (Technical Research)

Siber güvenliğin temeli olan ağ ve web teknolojileri üzerine detaylı incelemelerim.

* **📄 `Network_Infrastructure_Research.pdf`** (Ağ Yönetimi ve Sistem Altyapısı)
    * [cite_start]**İçerik:** IP atama süreçleri (DHCP), Ağ protokolleri (ARP, TCP/IP Handshake), DNS güvenliği (DNSSEC), Firewall yapılandırması ve Ölçeklenebilirlik (Load Balancing). [cite: 1119, 1134, 1173, 1211, 1234]

* **📄 `Web_Architecture_Research.pdf`** (Web Teknolojileri ve Mimarisi)
    * [cite_start]**İçerik:** Front-End/Back-End iletişimi, HTTP vs HTTPS (SSL/TLS farkı), Web Sunucuları (Apache vs Nginx), Modern Web Mimarisi (CDN, Caching, Microservices). [cite: 4, 23, 121, 141, 162, 173]

* **📄 `OWASP_Top_10_Guide.pdf`**
    * [cite_start]**İçerik:** Web güvenliğindeki en kritik 10 riskin teorik analizi ve önleme yöntemleri (Injection, Broken Access Control, Cryptographic Failures vb.). [cite: 1041, 1056, 1084]

---

##  Yetkinlikler ve Araçlar

Bu çalışmalarda kullandığım teknolojiler ve edindiğim yetkinlikler:

* **Araçlar:** Burp Suite (Intruder, Repeater), Nmap, Browser DevTools.
* **Zafiyet Sınıfları:** XSS (Stored/DOM), SQL Injection, IDOR, Privilege Escalation, Logic Flaws.
* **Web Teknolojileri:** HTML/CSS/JS, HTTP/HTTPS Protokolleri, Web Sunucuları (Apache/Nginx).
* **Ağ Bilgisi:** TCP/IP, DNS, DHCP, Firewall, OSI Modeli.
* **Veritabanı:** SQL ve NoSQL kavramları.
