# Döviz İşlem Yönetimi - Hybrid

Modern, kullanıcı dostu döviz işlem yönetim sistemi.

## 🚀 Özellikler

- **İkili İşlem Türü**: Döviz Alış ve Satış işlemleri
- **Akıllı Müşteri Seçimi**: Hem arama hem dropdown ile müşteri seçimi
- **Canlı Kur Takibi**: Anlık döviz kurları ve otomatik kur doldurma
- **Otomatik Hesaplama**: Gerçek zamanlı işlem tutarı hesaplama
- **Durum Yönetimi**: İşlem durumlarını takip ve filtreleme
- **Çift Filtreleme**: İşlem türü ve durum bazlı filtreleme
- **İşlem Geçmişi**: Detaylı işlem kartları ve timeline
- **Responsive Tasarım**: Mobil ve masaüstü uyumlu
- **Keyboard Shortcuts**:
  - `Ctrl+S` - İşlemi kaydet
  - `Ctrl+R` - Formu temizle

## 🎨 Teknolojiler

- **Frontend**: HTML5, CSS3 (Custom Styling), Vanilla JavaScript (ES6+)
- **UI Components**: Font Awesome Icons, Responsive Design (Mobile-first)
- **Data Storage**: LocalStorage (Demo), Ready for Backend API Integration
- **Deployment**: Vercel

## 📊 Durum Tipleri

- ✅ **Ödeme İçin Hazır** - İşlem ödeme için hazır
- ⏳ **Ödeme Bekleniyor** - Ödeme beklenen işlemler
- 🔄 **Eşleşmeyen Banka Transferleri** - Eşleşmeyen transferler
- ⏱️ **Ödeme Onayı Bekleniyor** - Onay sürecindeki işlemler
- ✓ **Tamamlandı** - Tamamlanmış işlemler
- ✗ **İptal Edildi** - İptal edilen işlemler

## 🌐 Canlı Demo

**Production:** [https://doviz-islem-a6xkdlt06-caglar-ozyildirims-projects.vercel.app](https://doviz-islem-a6xkdlt06-caglar-ozyildirims-projects.vercel.app)

**GitHub:** [https://github.com/caglarozyildirim/doviz-islem-app](https://github.com/caglarozyildirim/doviz-islem-app)

## 💻 Kurulum

```bash
# Repository'yi klonlayın
git clone https://github.com/caglarozyildirim/doviz-islem-app.git

# Proje dizinine gidin
cd doviz-islem-app

# index.html dosyasını tarayıcıda açın
open index.html
```

## 🔧 API Entegrasyonu

Sistem backend API entegrasyonu için hazır:

```javascript
// Müşteri listesi - API'den gelecek
const customerList = await fetch('/api/customers').then(r => r.json());

// Kur bilgileri - API'den gelecek
const currencyRates = await fetch('/api/rates').then(r => r.json());

// İşlem kaydetme - API'ye gönderilecek
await fetch('/api/transactions', {
  method: 'POST',
  body: JSON.stringify(transactionData)
});
```

## 📱 Ekran Görüntüleri

### Ana Ekran
![Ana Ekran](./screenshots/main.png)

### İşlem Geçmişi
![İşlem Geçmişi](./screenshots/history.png)

## 🤝 Katkıda Bulunma

1. Fork edin
2. Feature branch oluşturun (`git checkout -b feature/amazing-feature`)
3. Değişikliklerinizi commit edin (`git commit -m 'Add some amazing feature'`)
4. Branch'inizi push edin (`git push origin feature/amazing-feature`)
5. Pull Request açın

## 📄 Lisans

Bu proje MIT lisansı altında lisanslanmıştır.

## 👨‍💻 Geliştirici

**Çağlar Özyıldırım**

---

⭐ Bu projeyi beğendiyseniz yıldız vermeyi unutmayın!