Elektrik Tüketim ve Tahsilat Verisi Analizi (Case Study 02)

Bu proje, farklı ilçelerdeki elektrik tüketim alışkanlıklarını ve fatura ödeme (tahsilat) performanslarını analiz etmek amacıyla hazırlanmıştır. Proje kapsamında ham veriler üzerinde keşifsel veri analizi (EDA) yapılmış, veriler görselleştirilmiş ve müşteri segmentasyonu yapılarak veriye dayalı iş önerileri (storytelling) sunulmuştur.

Proje Yapısı

Proje dosyaları aşağıdaki yapıya uygun olarak düzenlenmiştir:

* **`data/`**: Analizde kullanılan ham ve işlenmiş Excel veri setlerini içerir.
* **`notebooks/`**: Veri analizi süreçlerini adım adım gösteren Jupyter Notebook dosyalarını içerir.
* **`outputs/figures/`**: Analiz sonucunda üretilen önemli görselleştirmeleri içerir.
* **`requirements.txt`**: Projenin çalışması için gereken Python kütüphanelerini ve sürümlerini listeler.

Notebook İçerikleri

Proje, birbirini takip eden 3 ana notebook'tan oluşmaktadır:

1.  **`notebook_01_veri_kesfi.ipynb`**: Ham verilerin yüklenmesi, tanımlayıcı istatistiklerin çıkarılması, eksik/aykırı değerlerin (outlier) tespiti ve verilerin birleştirilerek analize hazır hale getirilmesi.
2.  **`notebook_02_gorsellestirme.ipynb`**: Hazırlanan veriler üzerinden Matplotlib ve Seaborn kullanılarak tüketim dağılımları, mevsimsel trendler ve zamanında/geç ödeme oranlarının görselleştirilmesi.
3.  **`notebook_03_veri_hikayesi.ipynb`**: Açık uçlu analiz tekniğiyle hipotezlerin test edilmesi, müşteri gruplarının segmentasyonu ve elde edilen bulgularla stratejik iş önerileri geliştirilmesi.

Kullanılan Teknolojiler

* **Dil:** Python 3
* **Veri Manipülasyonu:** Pandas, NumPy
* **Veri Görselleştirme:** Matplotlib, Seaborn
* **Geliştirme Ortamı:** Jupyter Notebook / Google Colab
