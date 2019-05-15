<p align="center">
<a href="#" target="_blank">
 <img src="https://colab.research.google.com/assets/colab-badge.svg" width="110" height="50" border="10" />
</a>
</p>  

# Varyans
Varyans ile ilgili Soru ve Çözümü

## Soru: Varyans
İçerisinde Mavi ve Yeşil topların bulunduğu bir torbadan 2 top çekiliyor.Mavi top gelme sayısına ait kesikli olasılık dağılımını bulunuz.
Kesikli olasılık dağılımına ait Beklenen Değer "E[X]" yardımı ile Varyans "Var[X]" hesabını yapınız.

(Torbada bulunan Yeşil ve Mavi Top Sayıları Kullanıcı Tarafından Girilecektir.)

## Çözüm:
Yeşil: 4 ve Mavi: 3 ise

 Yeşil-Yeşil Durmu: P(X=0) = 4/7*3/6= 2/7
 
 Yeşil-Mavi veya Mavi-Yeşil Durumu: P(X=1) = 4/7*3/6+3/7*4/6= 4/7
 
 Mavi-Mavi Durumu: P(X=2) = 3/7*2/6= 1/7
 
 E[X] = ΣxP(X=x) = 0*2/7 + 1*4/7 + 2*1/7 = 6/7
 
 E[X^2] = Σx^2*P(X=x) = (0^2)*2/7 + (1^2)*4/7 + (2^2)*1/7 = 8/7

 Var[X] = E[X^2]-(E[X])^2 = 8/7 - (6/7)^2 = 20/49
 
## Açıklama:
