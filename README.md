# SelectionSortProject
[22,27,16,2,18,6] 

İlk aşama: [2,27,16,22,18,6] 
2. aşama: [2,27,16,22,18,6] 
3. aşama: [2,6,16,22,18,27] 
4. aşama: [2,6,16,18,22,27]

Big-O: => Işlemler n'den 1'e kadar gidecegi için, 1'den n'e kadar olan sayıların toplamıi sonucu çıkacak.
n.(n+1)/2
= n^2
=> o(n^2)

Zaman Karmaşıklığı: sıralamada bu şekilde [6,2,16,18,22,27] olacağı için 6 = Düşük , 27 = Yüksek ve 18 = Orta olacaktır. Bu durumda 18 sayıda Ortalama Durum için uygun oluyor.

Soru 2: [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

İlk aşama: [2,3,5,8,7,9,4,15,6]
2. aşama: [2,3,4,8,7,9,5,15,6]
3. aşama: [2,3,4,5,7,9,8,15,6]
4. aşama: [2,3,4,5,6,9,8,15,7]


