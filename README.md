#  Binary Search Tree Projesi www.patika.dev 

**Patika - Veri Yapıları ve Algoritmalar Dersinin Binary Search Tree Projesidir www.patika.dev**

## Binary Search Tree Projesi

------------------------------

### [7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Search-Tree aşamalarını yazınız.

    1. Aşama ->        2   => 2 elemanını root olarak seçtik.
                    /     \
    2. Aşama ->    1       7   => 1 elemanı root'un solunda, 7 ise sağındadır.
                  /      /   \
    3. Aşama ->  0      5     8  => 0 elemanı 2'den ve 1'den küçük olduğu için soldadır. 5, 2'nin sağında; 7'nin solundadır. 8, 2 ve 7'nin sağındadır.
                      /   \    \
    4. Aşama ->      3     6    9  => 3, 2'nin sağında; 7 ve 5'in solundadır. 6; 2'nin sağında, 7'nin solunda ve 5'in sağındadır. 9; 2,7 ve 8'in sağındadır.
                      \
    5. Aşama ->        4   => 4; 2'nin sağında, 7 ve 5'in solunda, 3'ün sağındadır.
                       
- Bu dizide root **2**'dir. Root'un sağında **7**, solunda **1** vardır.
