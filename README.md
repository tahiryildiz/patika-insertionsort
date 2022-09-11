# Insertion Sort Projesi - Patika.dev
Patika.dev Modul 2 - Proje 1 Insertion Sort

## Girdi
[22,27,16,2,18,6]

## İstenenler
1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.
3. Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

### 1- Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Dizi içerisindeki elemanlara tek tek bakıp küçük olanı başa alıyor:

[22,27,16,2,18,6]
[2,27,16,22,18,6]
[2,6,16,22,18,27]
[2,6,16,18,22,27]

### 2- Big-O gösterimini yazınız.

O(n2)

### 3- Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.

### 4- Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.

[2,6,16,18,22,27] Sıralamasına göre 18 ortalarda olduğundan average case'e girer.