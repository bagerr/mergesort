Problem
[16,21,11,8,12,22] -> Merge Sort


Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Çözüm

Splitting  [16, 21, 11, 8, 12, 22]

Splitting  [16, 21, 11]

Splitting  [16]

Merging  [16]

Splitting  [21, 11]

Splitting  [21]

Merging  [21]

Splitting  [11]

Merging  [11]

Merging  [11, 21]

Merging  [11, 16, 21]

Splitting  [8, 12, 22]


Splitting  [8]

Merging  [8]

Splitting  [12, 22]

Splitting  [12]

Merging  [12]

Splitting  [22]

Merging  [22]

Merging  [12, 22]

Merging  [8, 12, 22]

Merging  [8, 11, 12, 16, 21, 22]

[8, 11, 12, 16, 21, 22]



Problem

Big-O gösterimini yazınız.


Çözüm

O(nlogn)
