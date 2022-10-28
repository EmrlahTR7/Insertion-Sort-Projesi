# Insertion-Sort-Projesi 
# www.patika.dev 

#  [22,27,16,2,18,6] -> Insertion Sort
# 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.
- [22,27,16,2,18,6]
 - 1. adım. Dizideki en küçük sayıyı bulup ilk sıradaki sayı ile yer değiştiriyoruz.   [2,27,16,22,18,6] n 
 - 2. adım. Dizideki en küçük 2. sayıyı bulup 2. sıradaki sayı ile yer değiştiriyoruz. [2,6,16,22,18,27] n-1
 - 3. adım. Dizideki en küçük 3. sayıyı bulup 3. sıradaki sayı ile yer değiştiriyoruz. [2,6,16,22,18,27] n-2 (dizideki 3. en küçük sayı 3. sırada olduğu için değişme olmaz)
 - 4. adım. Dizideki en küçük 4. sayıyı bulup 4. sıradaki sayı ile yer değiştiriyoruz. [2,6,16,18,22,27] 1
 - Dizideki sıralama bitmiştir.
 
 # Big-O gösterimini yazınız.
 - O(n^2)
 
 # Time Complexity: Average case: Aradığımız sayının ortada olması,Worst case: Aradığımız sayının sonda olması, Best case: Aradığımız sayının dizinin en başında olması.
 # Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.
 [2,6,16,18,22,27]
 - Average case: Aradığımız sayının ortada olması, kapsamına girer.
 
 # [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.
 
 - 1. adım. Dizideki en küçük sayıyı bulup ilk sıradaki sayı ile yer değiştiriyoruz.    [2,3,5,8,7,9,4,15,6] 
 - 2. adım. Dizideki en küçük 2. sayıyı bulup 2. sıradaki sayı ile yer değiştiriyoruz.  [2,3,5,8,7,9,4,15,6]
 - 3. adım. Dizideki en küçük 3. sayıyı bulup 3. sıradaki sayı ile yer değiştiriyoruz.  [2,3,4,8,7,9,5,15,6]
 - 4. adım. Dizideki en küçük 4. sayıyı bulup 4. sıradaki sayı ile yer değiştiriyoruz.  [2,3,4,5,7,9,8,15,6]
