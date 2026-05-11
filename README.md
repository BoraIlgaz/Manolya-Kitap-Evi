# 🌸 Manolya Kitap Evi - Dijital & Ücretsiz Kütüphane Platformu

**Manolya Kitap Evi**, okuma alışkanlığını herkes için erişilebilir, keyifli ve sürdürülebilir kılmak amacıyla **MVC** mimarisiyle geliştirilmiş, tamamen ücretsiz bir dijital kütüphane platformudur. Kullanıcılar her yerden kitaplara ulaşabilirken, yöneticiler gelişmiş bir **Admin Panel** üzerinden tüm kütüphane ekosistemini ve SQL veritabanını kontrol edebilir.

## ✨ Vizyon & Misyon
* **Vizyonumuz:** Okumayı herkes için erişilebilir bir alışkanlığa dönüştüren sıcak bir topluluk oluşturmak. Her yaştan okuyucunun kendini evinde hissedeceği bir dijital kütüphane olmak.
* **Misyonumuz:** Kitap severlere ücretsiz, hızlı ve güvenli bir şekilde kitaplara ulaşabilecekleri bir alan sunmak. Okurken rahat hissettirmek ve her an keşif imkanı sağlamak.

---

## 🖼️ Proje Ekran Görüntüleri (Modüller)

Aşağıda platformun kullanıcı arayüzü ve yönetim paneline dair ekran görüntüleri yer almaktadır:

### 📱 Kullanıcı Arayüzü
| **Görsel** | **Açıklama** |
| :---: | :--- |
| ![Anasayfa](Screenshots/r1.jpg) | **Anasayfa:** Dinamik istatistiklerin ve popüler kitapların listelendiği ana karşılama ekranı. |
| ![Kitaplar](Screenshots/r2.jpg) | **Dijital Katalog:** Veritabanından çekilen tüm kitapların dinamik olarak listelendiği keşif alanı. |
| ![Hakkımızda](Screenshots/r3.jpg) | **Kurumsal Vizyon:** Platformun amacını ve topluluk değerlerini yansıtan bölüm. |
| ![İletişim](Screenshots/r4.jpg) | **İletişim:** Kullanıcı geri bildirimleri için kurgulanmış etkileşim sayfası. |

### 🔐 Yönetim Paneli (Admin Panel & CMS)
| **Görsel** | **Açıklama** |
| :---: | :--- |
| ![Admin Giriş](Screenshots/r5.jpg) | **Güvenli Erişim:** Admin paneline giriş için kullanılan yetkilendirme katmanı. |
| ![Dashboard](Screenshots/r6.png) | **Admin Dashboard:** Sistemin genel durumunu ve SQL verilerini takip etmeyi sağlayan yönetim merkezi. |
| ![Kitap Ekleme](Screenshots/r7.png) | **İçerik Yönetimi (CRUD):** Kitap ekleme, silme ve güncelleme işlemlerinin yapıldığı kontrol sayfası. |

---

## 🛠️ Teknik Özellikler ve Mimari

Bu proje, **Separation of Concerns (Sorumlulukların Ayrılması)** prensibine dayalı profesyonel bir mimari ile inşa edilmiştir:

* **MVC Design Pattern:** Kodun sürdürülebilirliğini artırmak için Model, View ve Controller katmanları birbirinden ayrılmıştır.
* **Dinamik Veri Yönetimi:** "En Çok Okunanlar" ve "Yeni Eklenenler" bölümleri, SQL sorguları aracılığıyla veritabanından dinamik olarak çekilir.
* **Full CRUD Operasyonları:** Admin panel üzerinden veritabanındaki kitap verileri üzerinde tam kontrol (Create, Read, Update, Delete) sağlanır.
* **İstatistiksel Analiz:** Kullanıcıların okuma verilerini işleyen ve Dashboard üzerinden görselleştiren mantıksal katman mevcuttur.

## 🚀 Kullanılan Teknolojiler
* **Backend:** [C#, Dotnet Framework]
* **Veritabanı:** SQL (İlişkisel Veri Modeli)
* **Frontend:** HTML5, CSS3, JavaScript, Bootstrap
* **Mimari:** MVC (Model-View-Controller)

## 🔓 Açık Kaynak ve Lisans
Bu proje, dijital okuma kültürüne katkı sağlamak amacıyla **ücretsiz ve açık kaynaklı** olarak paylaşılmıştır.
* **Lisans:** MIT Lisansı (Özgürce kullanılabilir, geliştirilebilir ve dağıtılabilir).
