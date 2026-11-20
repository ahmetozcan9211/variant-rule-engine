# Ürün Varyant Kural Motoru

ERP'de satış belgelerine girilen ürün varyant seçimlerinin (renk, boyut, ambalaj vb.) tanımlı kurallara uyup uymadığını denetleyen; kuralların teknik bilgi gerekmeden arayüzden yönetildiği sistem.

> Bu depo bir proje vitrinidir. Kaynak kod paylaşılmamaktadır.

## Özellikler

- **Kural yönetimi:** Ürün veya ürün grubu bazında izinli ve yasak varyant değerleri, koşullu kurallar (bir seçim diğerini kısıtlar)
- **Varyant bölümleme:** Birleşik varyant kodlarını ayrı özelliklere ayırma ve ERP'nin beklediği XML formatına dönüştürme
- **Kontrol ve log:** Kurala uymayan belgeler listelenir, her kontrol kayıt altına alınır
- Varsayılan değer ayarları ve otomatik şema migrasyonu
- ERP veritabanına yalnızca okuma erişimi

Bu kurallar, satış ekibine anlık uyarı gönderen n8n otomasyonunun da temelini oluşturur.

## Teknolojiler

`React` · `TypeScript` · `Vite` · `Tailwind CSS` · `Framer Motion` · `Node.js` · `Express` · `PostgreSQL` · `Prisma` · `Next.js`
