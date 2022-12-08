# Insertion Sort Projesi
[Patika.dev](https://www.patika.dev/tr)

[22,27,16,2,18,6] -> Verilen Dizi

Birinci Sorunun Çözümü:
  1. Aşama: 22 ile 27 sıralı olduğundan ötürü bir değişiklik olmaz. [22,27,16,2,18,6]
  2. Aşama: 27 ile 16 sıralanır, 16 sola geçer. 16 sayısı 22 sayısından da küçük olduğundan ötürü 16 başa geçmiş olur. [16,22,27,2,18,6]
  3. Aşama: 2 sayısı 27'den küçük olduğundan onun sol tarafına geçer. En küçük sayı 2 olduğundan karşılaştırmalar bitince 2 başa geçmiş olur. [2,16,22,27,18,6]
  4. Aşama: 18 sayısı 27 ve hemen ardından 22 ile kıyaslanır, ikisinden de küçük bir sayı olduğu için 22'nin soluna geçer. [2,16,18,22,27,6]
  5. Aşama: 6 sayısı solundaki sayılarla kıyaslandıktan sonra 2'nin sağına geçer ve dizi sıralanmış olur. [2,6,16,18,22,27]

İkinci Sorunun Çözümü:
  Verilen dizinin Big-O Gösterimi: O(n^2)

Üçüncü Sorunun Çözümü:
  Yukarıda verilen dizi için "Time Complexity" değerleri: 
    Best Case: O(n),
    Average Case: O(n^2),
    Worst Case: O(n^2).

Dördüncü Sorunun Çözümü:
  18 sayısı sıralanmış dizide ortada yer alıyor, yani "Average Case" kapsamına girmektedir.
 
---

[7,3,5,8,2,9,4,15,6] -> Verilen İkinci Dizi


İkinci Dizinin İlk 4 Adımı:
  1. Adım: 3 ile 7 sayısı yer değiştirir. [3,7,5,8,2,9,4,15,6]
  2. Adım: 7 ile 5 sayısı yer değiştirir. [3,5,7,8,2,9,4,15,6]
  3. Adım: 7 ile 8 sayısı zaten sıralı olduğu için bir değişiklik olmaz. [3,5,7,8,2,9,4,15,6]
  4. Adım: 8 ile 2 yer değiştirir, devamında ise 2 sayısı en başa taşınır. [2,3,5,7,8,9,4,15,6]

