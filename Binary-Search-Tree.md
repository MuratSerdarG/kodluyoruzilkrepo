# Proje Sahibi: Patika.Dev 
# Proje Konusu: Veri Yapıları ve Algoritmalar
## Konu 1: Binary Search Tree
---
**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] -> Binary Search Tree**
- Binary-Search-Tree aşamalarını yazınız. Örn: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
---

#### 1-) Binary-Search-Tree aşamalarını yazınız.
![Binary search](https://user-images.githubusercontent.com/93589387/147054175-36ecc6e1-c034-450f-8299-0ee0b5f07477.jpg)
```sh
1.	“7” root değer belirlenir.
2.	“5” “7” den küçük olduğu için sola yazılır.
3.	“1” “7 ve 5” den küçük olduğu için “5”in soluna yazılır.
4.	“8” “7” den büyük olduğu için sağa yazılır.
5.	“3” “7 ve 5” den küçük, “1”den büyük olduğu için “1”in sağına yazılır.
6.	“6” “7”den küçük “5”den büyük olduğu için “5”in sağına yazılır.
7.	“0” “7 ve 5 ve 1”den küçük olduğu için “1”in soluna yazılır.
8.	“9” “7 ve 8”den büyük olduğu için “8”in sağına yazılır.
9.	“4” “7 ve 5”den küçük “1 ve 3” den büyük olduğu için “3”ün sağına yazılır.
10.	“2” “7 ve 5”den küçük “1”den büyük “3”den küçük olduğu için “3”ün soluna yazılır.
```
