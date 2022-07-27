# insertion-sort-projesi

* [22,27,16,2,18,6] - Insertion Sort

1-Yukarı verilen verilebilir sıralama düzenini aşamalarını not edin.

2-Big-O gösterimini yazınız.

3-Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

4-Dizi sıralandıktan sonra 18 sayı hangi davaya girer? Yazınız.

5-[7,3,5,8,2,9,4,15,6] dizinin Insert sort'a göre ilk 4 adımını yazın.

Insertion Sort Aşamaları

[22,27,16,2,18,6] -----> (n)

[2|,27,16,22,18,6] -----> (n-1)

[2,6|,16,22,18,27] -----> (n-2)

[2,6,16,18|,22,27] -----> (n-3) # 16 zaten 3.sırada olduğu için 18' e geçtik. #

*Big O Notation Gösterimi

WORST CASE -----> O(n²) = n+(n-1)+(n-2)...+1

AVERAGE CASE -----> O(n²)

BEST CASE -----> O(n)

Time Complexity
WORST CASE -----> [27,22,18,16,6,2]

BEST CASE -----> [2,6,16,18,22,27]

*18 Sayısının Case Durumu

Dizimizi küçükten büyüğe sıralarız. Dizimiz [2,6,16,18,22,27] şeklini alır ve 18 sayısı bu dizinin ortanca değer olduğundan average case diyebiliriz.

*[7,3,5,8,2,9,4,15,6] Dizisinin İlk 4 Adımı

1- [2|,3,5,8,7,9,4,15,6]

2- [2,3|,5,8,7,9,4,15,6]

3- [2,3,4|,8,7,9,5,15,6]

4- [2,3,4,5|,7,9,8,15,6]


https://app.patika.dev/
