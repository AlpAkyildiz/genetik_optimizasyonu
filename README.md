# genetik_optimizasyonu

Akıllı Depoda Raf Boyutlarının Genetik Algoritma ile Optimizasyonu

Bu proje, bir lojistik firmasının akıllı depo sisteminde kullanılacak rafların yükseklik ve derinlik değerlerini optimize etmek için Genetik Algoritma (GA) yöntemini kullanır. Amaç, depo verim puanını maksimize ederken tüm fiziksel kısıtlara uyum sağlamaktır.

 Problemin Tanımı

Amaç, raf yüksekliği (x₁) ve raf derinliği (x₂) değerlerini seçerek depo verim puanını artırmaktır. Kullanılan amaç fonksiyonu:    

    y=4x1​+3x2​−0.5x1​x2​

    Kısıtlar: 
      x1​ + x2​ ≤ 8
      x2​ ≥ 1.5
      2 ≤ x1​ ≤ 6
      1 ≤ x2 ​≤ 4

Fonksiyon doğrusal olmadığı için çözüm Genetik Algoritma ile gerçekleştirilmiştir.

 Genetik Algoritma Süreci

GA aşağıdaki bileşenlerle uygulanmıştır:

     Başlangıç Popülasyonu: Rastgele bireylerden oluşturulur
  
     Fitness: Amaç fonksiyonu + kısıt kontrolü
  
     Seçim: Tournament Selection
  
     Çaprazlama: Ara değerleme (interpolation) crossover
  
     Mutasyon: Rastgele küçük değişiklikler
  
     Nesil Geliştirme: Çocuklar → yeni popülasyon

Çıktılar

     En iyi raf yüksekliği (x₁)
  
     En iyi raf derinliği (x₂)
  
     Maksimum verim puanı (fitness değeri)
  
     Nesillere göre iyileşme grafiği

Kullanılan Teknolojiler

     Python
     NumPy
     Matplotlib
     Jupyter Notebook

Bu proje eğitim amaçlıdır. Serbestçe kullanılabilir.
