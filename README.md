# Makine Öğrenmesi Örneği
                               
-1. Yöntem

Örnek uygulamamızda, ülkelere göre kişi başına gelir ve ülkelere göre yaşam standartı adlı verilerle, Doğrusal Regrasyon Algoritmasını kullanarak sınıflandırma yaptık. (Model Tabanlı Öğrenme)

Yaşam_standartı = teta0 + teta1 * kişi_başına_gelir 
Fonksiyonu ile ülkelerin yaklaşık yaşam standartını bulacağız.
bu modelde 2 parametre vardır,
işte burda doğrusal regrasyon algoritması devreye girer.
Linkte verdiğim datasetlerle birlikte jupyter-notebook daki kodları çalıştırırsanız (Açıklamalı bir şekilde yazdım) teta0 = 4.85 , teta1 = 4.91 * e-05 sonuçlarını alırsınız. ve bu fonksiyonu kullanarak ülkelerin yaşam standartalarını grafikte belirledik.
 
-2. Yöntem

Bu yöntemde ise aynı örneği K-En Yakın Komşu Algoritması (KNN) ile çözdük.

k=3 olarak aldık. Bu durumda en yakın 3 komşuya göre sınıflandırma yapılacaktır.
Örnek veri setine katılacak olan yeni verinin, mevcut verilere göre uzaklığı tek tek hesaplanır. 
İlgili uzaklık fonksiyonları yardımıyla.
İlgili uzaklılardan en yakın k komşu ele alınır. 
Öznitelik değerlerine göre k komşu veya komşuların sınıfına 
atanır.
