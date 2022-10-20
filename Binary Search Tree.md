##Binary Search Tree Projesi

Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

***Answer

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]

İlk node 7 olduğu için root olarak seçeriz.

Dizinin devam eden elemanlarına tek tek büyük mü küçük mü sorusu sorularak yerleştirme yapılır.
5 < 7, 1 < 7, 8 > 7, 3 < 7, 6 < 7, 0 < 7, 9 > 7, 4 < 7, 2 < 7 soruları ile 10 adımda oluşturulur.


               7
              / \
             5   8
            / \    \
           1   6    9
          / \
         0   3
             / \
            2    4