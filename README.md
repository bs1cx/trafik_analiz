# İstanbul Trafik Endeksi Verisi

Bu proje, İstanbul'daki trafik yoğunluğunu analiz etmek ve görselleştirmek için Dash ve Plotly kullanarak interaktif bir web uygulaması oluşturur. Kullanıcılar, trafik verilerini tarih aralığı ve trafik kategorisi (Yüksek, Orta, Düşük) gibi filtreleme seçenekleri ile inceleyebilir. Ayrıca, gelecekteki trafik tahminleri için ARIMA modelini kullanan bir tahmin aracı da mevcuttur.

## Proje İçeriği

- **Veri Kümesi**: İstanbul'un trafik endeksi verisi, tarih ve trafik endeksi gibi bilgiler içerir. Bu veriler, farklı tarih aralıkları ve trafik kategorilerine göre filtrelenebilir.
- **Web Uygulaması**: Dash framework'ü kullanarak interaktif bir web uygulaması geliştirilmiştir.
- **Grafikler ve Görselleştirme**: Plotly kullanarak zaman serisi grafikleri, trafik endeksi dağılımı ve tahminler görselleştirilmiştir.

## Özellikler

- **Tarih Aralığı Seçimi**: Kullanıcılar, veri kümesindeki trafik endeksi verilerini belirli bir tarih aralığına göre filtreleyebilir.
- **Trafik Kategorisi Seçimi**: Kullanıcılar, trafik verilerini "Yüksek", "Orta" veya "Düşük" kategorilerinde filtreleyebilir.
- **Trafik Endeksi Zaman Grafiği**: Trafik endeksi, zaman içerisinde değişimi gösteren bir çizgi grafiği ile görselleştirilmiştir.
- **Gelecek Trafik Tahminleri**: ARIMA modeli kullanılarak, mevcut trafik verilerine dayalı gelecekteki trafik endeksi tahminleri yapılır ve görselleştirilir.

## Kullanım

### Gereksinimler

- Python 3.x
- Dash
- Pandas
- Plotly
- Statsmodels (ARIMA modeli için)
- Matplotlib ve Seaborn (diğer grafikler için)

### Kurulum

1. Bu projeyi bilgisayarınıza klonlayın:
   ```bash
   git clone https://github.com/username/istanbul-trafik-endeksi.git
