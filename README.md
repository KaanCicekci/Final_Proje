# Final_Proje
## Karbon Ayak İzi Hesaplayıcı
## 1. Projenin Amacı ve Kapsamı

Bu projenin temel amacı, bireylerin ya da kurumların günlük faaliyetleri sonucunda atmosfere saldıkları **karbondioksit (CO₂)** miktarını, yani *karbon ayak izini* hesaplayarak farkındalık yaratmaktır.

Python programlama dili kullanılarak geliştirilecek bu uygulama:
- Kullanıcıdan alınan temel verilerle karbon salınımını tahmin edecek,
- Elde edilen sonuçları anlaşılır grafiklerle sunacaktır.

### Analiz Edilecek Faaliyetler:
- 🚗 **Ulaşım:** Otomobil, otobüs, uçak vb.
- 💡 **Enerji Tüketimi:** Elektrik ve doğalgaz kullanımı
- 🍽️ **Beslenme Alışkanlıkları:** Et, süt, sebze tüketimi
- ♻️ **Geri Dönüşüm ve Atık Yönetimi**

**Hedef:** Kullanıcıya yıllık karbon ayak izi (ton CO₂ / yıl) bilgisi ve bireysel azaltım önerileri sunmak.

---

## 2. Kullanılacak Teknolojiler ve Kütüphaneler

Projede kullanılacak başlıca Python kütüphaneleri:

- **pandas:** Veri toplama ve işleme  
- **NumPy:** Sayısal hesaplamalar  
- **matplotlib & seaborn:** Veri görselleştirme  
- _(Opsiyonel)_ **Streamlit:** Web arayüzü geliştirmek için

---

## 3. Veri Kaynakları ve Hesaplama Metodolojisi

Her faaliyet türü için emisyon hesaplamalarında **uluslararası geçerliliği olan katsayılar** kullanılacaktır.  
Örnek: `1 litre benzin = 2.31 kg CO₂`

### Kullanılabilecek Güvenilir Kaynaklar:
- [Real Python – Matplotlib Guide](https://realpython.com/python-matplotlib-guide/)
- [Pandas Kullanım Rehberi](https://pandas.pydata.org/docs/user_guide/index.html)
- [Nature.org Karbon Ayak İzi Hesaplayıcı](https://www.nature.org/en-us/get-involved/how-to-help/carbon-footprint-calculator/)
- [CarbonFootprint.com Hesaplayıcı](https://www.carbonfootprint.com/calculator.aspx)

Bu kaynaklar sayesinde karbon hesaplamalarında bilimsel doğruluk sağlanacaktır.

---

## 4. Yapılacak İşler

1. ✅ Konu belirleme ve kaynak tarama  
2. 📊 Veri toplama ve hesaplama formüllerinin oluşturulması  
3. 🧮 Python ile hesaplama modülünün geliştirilmesi  
4. 📈 Görselleştirme bileşenlerinin eklenmesi  
5. 🖥️ Opsiyonel arayüz geliştirme (Streamlit)  
6. 🧪 Test, doğrulama ve raporlama

