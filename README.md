<p align="center">
<a href="#" target="_blank">
 <img src="https://colab.research.google.com/assets/colab-badge.svg" width="110" height="50" border="10" />
</a>
</p>  

# Varyans
Varyans ile ilgili Soru ve Çözümü

## Soru: Varyans
İçerisinde Kırmızı ve Beyaz kartların bulunduğu bir torbadan 2 kart çekiliyor. Kırmızı kart gelme sayısına ait kesikli olasılık dağılımını ve kesikli olasılık dağılımına ait beklenen değeri "E[X]" hesaplayarak Varyansın "Var[X]" ne olacağını bulunuz.

## Çözüm:
Beyaz Kart: 4 ve Kırmızı Kart: 3 olursa

Beyaz-Beyaz Durumu: P(X=0) = 4/7x3/6 = 2/7

Beyaz-Kırmızı veya Kırmızı-Beyaz Durumu: P(X=1) = 4/7x3/6 + 3/7x4/6 = 4/7

Kırmızı-Kırmızı Durumu: P(X=2) = 3/7x2/6 = 1/7

E[X] = ΣxP(X=x) = 0x2/7 + 1x4/7 + 2x1/7 = 6/7

E[X^2] = Σx^2*P(X=x) = (0^2)x2/7 + (1^2)x4/7 + (2^2)x1/7 = 8/7

Var[X] = E[X^2] - (E[X])^2 = 8/7 - (6/7)^2 = 20/49
 
## Açıklama:
