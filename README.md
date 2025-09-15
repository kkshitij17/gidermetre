# 💰 Gidermetre

**Sürekli giderlerinizi görün** - Modern ve kullanıcı dostu masraf takip uygulaması

## 🎯 Özellikler

### 📊 **Gerçek Zamanlı Takip**
- **Canlı sayaç**: Siteye girdiğinizden beri sürekli artan masraf gösterimi
- **Saniyede 10 güncelleme**: Çok smooth ve hızlı masraf artışı
- **Akıllı süre formatı**: "Son 2 dakika, 30 saniyedir sitedesiniz"

### 💸 **Kapsamlı Masraf Kategorileri**

#### 📅 **Günlük Masraflar**
- 🍽️ Yemek
- ☕ Çay/Kahve  
- 🚬 Sigara
- 🚌 Ulaşım
- 💰 Diğer

#### 🗓️ **Aylık Masraflar**
- 🏠 Kira
- ⚡ Elektrik
- 💧 Su
- 🔥 Doğalgaz
- 🌐 İnternet
- 📱 Telefon
- 🏢 Aidat
- 🚐 Servis Ücreti
- ⛽ Araç Yakıtı
- 🏥 SGK & Bağkur
- 🎓 Okul Taksidi
- 🏦 Kredi Taksiti
- 💳 Kredi Kartı
- 💪 Spor Salonu (Aylık)
- 📺 Dijital Abonelikler

#### 📅 **Yıllık Masraflar**
- 🔧 Araç Bakımı
- 🚗 Araç Sigortası
- 📄 MTV
- 🛡️ Araç Kaskosu
- 🔍 Araç Muayenesi
- 🏠 DASK
- ❤️ Sağlık Sigortası
- 🏛️ Emlak Vergisi
- 🏖️ Tatil Masrafı
- 🏋️ Spor Salonu (Yıllık)

### ➕ **Özel Kategori Ekleme**
- Her kategori türü için özel masraf kalemi ekleme
- Dinamik kategori yönetimi
- Kolay silme ve düzenleme

### 📱 **Modern UI/UX**
- **Responsive tasarım**: Mobil, tablet ve desktop uyumlu
- **Fixed header**: Sürekli görünür gider özeti
- **Kompakt kartlar**: Temiz ve düzenli görünüm
- **Akıllı input**: Tıklandığında otomatik seçim
- **Smooth animasyonlar**: Modern geçişler

### 🔒 **Gizlilik & Güvenlik**
- **Hiçbir veri sunucuda depolanmaz**
- **Tüm veriler tarayıcınızda güvenle saklanır**
- **Açık kaynak kodlu**

## 🚀 Kullanım

1. **Masraf kategorilerine tutarları girin**
2. **Dashboard'da real-time güncellemeleri görün**
3. **Özel kategoriler ekleyin**
4. **Canlı sayaçla sürekli artan masrafınızı takip edin**

## 🛠️ Teknik Detaylar

### **Teknolojiler**
- **Vue.js 3**: Modern JavaScript framework
- **TailwindCSS**: Utility-first CSS framework
- **LocalStorage**: Tarayıcı tabanlı veri saklama
- **GitHub Pages**: Statik hosting

### **Hesaplama Mantığı**
```javascript
// Toplam aylık = günlük*30 + aylık + yıllık/12
totalMonthlyExpense = (dailyTotal * 30) + monthlyTotal + (yearlyTotal / 12)

// Günlük toplam = günlük + aylık/30 + yıllık/365  
dailyExpenseTotal = dailyTotal + (monthlyTotal / 30) + (yearlyTotal / 365)

// Canlı masraf = (günlük + aylık) * geçen_saniye
liveExpense = (dailyExpensePerSecond + monthlyExpensePerSecond) * sessionSeconds
```

### **Performans**
- **Saniyede 10 güncelleme**: Smooth masraf artışı
- **Efficient rendering**: Sadece değişen veriler güncellenir
- **Memory management**: Otomatik cleanup

## 🌟 Açık Kaynak

Bu proje tamamen açık kaynak kodludur. Kodları inceleyebilir, katkıda bulunabilir veya kendi projelerinizde kullanabilirsiniz.

**GitHub**: [https://github.com/iltekin/masrafmetre](https://github.com/iltekin/masrafmetre)

## 👨‍💻 Geliştirici

**@sezeriltekin** - [Twitter](https://x.com/sezeriltekin)

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

---

**© 2024 Gidermetre** - Masraflarınızı kontrol altında tutun! 💰
