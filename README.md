# Projeler

file:///C:/Users/Ceylan/OneDrive/Masa%C3%BCst%C3%BC/index.html

file:///C:/Users/Ceylan/OneDrive/Masa%C3%BCst%C3%BC/goggle.html

roje Açıklaması:
Bu projede verilen iki farklı sıralama algoritması olan Insertion Sort ve Selection Sort adım adım uygulanarak hem algoritma mantıkları hem de Big-O analizleri ele alınmıştır.

🟩 Insertion Sort Uygulaması
Veri Seti: [22, 27, 16, 2, 18, 6] Sıralama Aşamaları:

[22, 27, 16, 2, 18, 6]

[16, 22, 27, 2, 18, 6]

[2, 16, 22, 27, 18, 6]

[2, 16, 18, 22, 27, 6]

[2, 6, 16, 18, 22, 27]

Big-O Gösterimi:

Best Case: \O(n) \

Average/Worst Case: \O(n^2) \

18 sayısı sıralı dizide nerede?:

[2, 6, 16, 18, 22, 27] → Orta kısımda yer aldığı için Average Case kapsamındadır ✅

🟨 Selection Sort — İlk 4 Adım
Veri Seti: [7,3,5,8,2,9,4,15,6] Adımlar:

[2,3,5,8,7,9,4,15,6]

[2,3,5,8,7,9,4,15,6]

[2,3,4,8,7,9,5,15,6]

[2,3,4,5,7,9,8,15,6]


Merge Sort Aşamaları:
Diziyi ikiye böl: [16, 21, 11] ve [8, 12, 22]

Alt dizileri tekrar böl: [16], [21, 11] ve [8], [12, 22]

Alt dizileri tekrar böl: [21], [11] ve [12], [22]

Alt dizileri sıralayıp birleştir: [21, 11] → [11, 21] [12, 22] → [12, 22]

Birleştir: [16] ve [11, 21] → [11, 16, 21] [8] ve [12, 22] → [8, 12, 22]

Son birleştirme: [11, 16, 21] ve [8, 12, 22] → [8, 11, 12, 16, 21, 22]

⏱️ Big-O Gösterimi:
Worst Case: \O(n \\log n) \

Best Case: \O(n \\log n) \

Average Case: \O(n \\log n) \
