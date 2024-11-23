# Global-AI-Veri-Analizi-Bootcamp
# Video Game Reviews and Ratings Analysis

## **Proje Özeti**
Bu proje, video oyunlarıyla ilgili bir veri seti üzerinde yapılan **Keşifsel Veri Analizi (EDA)** çalışmasını içermektedir. Amacımız, oyunların **derecelendirmelerini**, **fiyatlandırma** ve **platformlar** gibi özelliklere göre analiz etmek ve kullanıcıların oyun tercihlerini anlamaktır.

Veri setinde, farklı **oyun türleri**, **platformlar**, **fiyatlar** ve **kullanıcı derecelendirmeleri** gibi çeşitli değişkenler bulunmaktadır. Bu proje, oyunların kullanıcılar tarafından nasıl değerlendirdiğini anlamak için bu verileri kullanır ve platformlar arası farkları ortaya koyar.

## **Veri Seti Özeti**
Bu projede kullanılan veri seti, **Video Game Reviews and Ratings** adlı bir veri kümesidir. Veri setinde yer alan başlıca sütunlar şunlardır:
- **Game Title**: Oyun ismi
- **User Rating**: Kullanıcı derecelendirmesi
- **Price**: Oyun fiyatı
- **Platform**: Oyunların yayınlandığı platformlar (PC, PlayStation, Xbox vb.)
- **Release Year**: Oyunların yayımlandığı yıl
- **Genre**: Oyun türü (macera, strateji, spor vb.)

Veri seti, oyunların platformlar, türler ve fiyatlarla nasıl ilişkili olduğunu anlamamıza olanak tanır. Ayrıca, **eksik veri analizi** ve **veri temizleme** adımlarını içerir.

## **Yapılan Analizler**
1. **Eksik Veri Analizi ve Doldurma**:
   - Eksik veriler tespit edilerek uygun yöntemlerle doldurulmuştur. Sayısal veriler **ortalama**, **medyan** gibi istatistiksel yöntemlerle, kategorik veriler ise **mod** ile doldurulmuştur.

2. **Veri Görselleştirme**:
   - Verinin dağılımını anlamak için **heatmap**, **kdeplot**, **lineplot** gibi görselleştirmeler kullanılmıştır.
   - **Platformlar** arasındaki farklılıklar, yıllık **kullanıcı derecelendirmeleri** ve **fiyat değişimlerine** dair grafikler oluşturulmuştur.

3. **Kategorik ve Sayısal Değişkenlerin Analizi**:
   - **Kategorik değişkenler**: Platform, oyun türü gibi kategorik değişkenler arasında analiz yapılmıştır.
   - **Sayısal değişkenler**: Kullanıcı derecelendirmeleri, fiyatlar gibi sayısal değişkenler arasındaki ilişkiler incelenmiştir.

4. **Trend Analizleri ve Yıllık Dağılımlar**:
   - **Kullanıcı derecelendirmelerinin yıllık değişimi** ve **platformlar arasındaki eğilimler** incelenmiştir.
   
## **Kullanılan Kütüphaneler**
- **Pandas**: Veri işleme ve analizi için kullanıldı.
- **NumPy**: Sayısal veri işleme ve hesaplamalar için kullanıldı.
- **Matplotlib** ve **Seaborn**: Veri görselleştirme için kullanıldı.
- **Scikit-learn**: Eksik veri doldurma ve modelleme işlemleri için kullanıldı.

## **Proje Adımları**
1. **Veri Yükleme ve Temizleme**: Veri seti yüklendi, eksik veriler tespit edilip uygun şekilde dolduruldu.
2. **Keşifsel Veri Analizi (EDA)**: Verinin dağılımı ve ilişkileri incelendi. Kategorik ve sayısal değişkenler arasındaki ilişkiler görselleştirildi.
3. **Görselleştirme ve Grafikler**: Sayısal ve kategorik verilerle ilgili görseller oluşturularak kullanıcı tercihlerinin analizi yapıldı.
4. **Sonuçlar ve Öneriler**: Kullanıcı tercihleri, platformlar arası farklar ve fiyatlandırma stratejileri üzerine öneriler sunuldu.

## **Sonuçlar ve Öneriler**
- **Platformlar**: PlayStation ve PC oyunları en yüksek puanları almış ve en fazla kullanıcı tarafından tercih edilmiştir.
- **Oyun Türleri**: Strateji ve macera türleri en yüksek kullanıcı derecelendirmelerine sahip olmuştur.
- **Fiyatlandırma**: Düşük fiyatlı oyunlar daha geniş bir kullanıcı kitlesine ulaşırken, yüksek fiyatlı oyunlar daha fazla kullanıcı derecelendirmesi almıştır.
- **Öneri**: Geliştiricilerin özellikle **PlayStation** ve **PC platformlarında, strateji ve macera türlerine odaklanması** önerilmektedir.

## **Gelecekteki Çalışmalar**
- Kullanıcı yorumlarını analiz etmek için **doğal dil işleme** (NLP) teknikleri kullanılabilir.
- Oyun içi etkileşim ve kullanıcı geri bildirimlerine dayalı olarak **kişiselleştirilmiş tavsiye sistemleri** geliştirilebilir.

---

### **Proje Linkleri**
- **Kaggle Notebook**: [Kaggle Proje Linki](kaggle-linkinizi-buraya-ekleyin)
- **GitHub Repo**: [GitHub Repo Linki](github-repo-linkinizi-buraya-ekleyin)

