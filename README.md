# Redux Contacts

React Native ile hazırlanmış, Redux kullanarak kişi ekleme ve listeleme uygulaması.

## Özellikler

- Kişi ekleme
- Kişi listesi görüntüleme
- Redux ile global state yönetimi
- React Navigation ile ekranlar arası geçiş

## Kurulum

1. **Projeyi klonla:**
   ```sh
   git clone https://github.com/kullaniciadi/reduxcontacts.git
   cd reduxcontacts
   ```

2. **Bağımlılıkları yükle:**
   ```sh
   npm install
   # veya
   yarn install
   ```

3. **Mobil uygulamayı başlat:**
   ```sh
   npx react-native run-android
   # veya
   npx react-native run-ios
   ```

## Kullanılan Teknolojiler

- React Native
- Redux & React-Redux
- React Navigation

## Klasör Yapısı

```
reduxcontacts/
├── App.tsx
├── src/
│   ├── navigators/
│   ├── redux/
│   ├── screens/
│   └── utils/
```

## Notlar

- Kişi eklerken isim ve telefon numarası zorunludur.
- Telefon numarası en az 11 karakter olmalıdır.
- Kişi eklendikten sonra ana ekrana yönlendirilir.

## Katkı

Katkıda bulunmak için lütfen bir pull request gönderin.

---

**Hazırlayan:**
