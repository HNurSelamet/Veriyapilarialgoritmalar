## Binary Search Tree Projesi

- - -

### Proje 3

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]  dizisinin Binary-Search-Tree aşamalarını yazınız.

Dizinin ilk elemanı olan 7 yi root olarak alıyoruz.
- - - 
1.ADIM :

          7
        /
      5
 - - -
        7
       /
      5
     /
    1
- - -
             7
           /   \
          5     8
         / 
        1
- - -
             7
           /   \
          5      8
         /
        1
          \3
- - -
              7
           /     \
          5       8
         /  \6
        1
          \3
- - -
              7
           /     \
          5       8
         /  \6
        1
       /  \
      0    3
 - - -
              7
           /     \
          5       8
         /  \       \
        1    6        9
       /  \
      0    3
 - - -
              7
           /     \
          5       8
         /  \       \
        1    6        9
       /  \
      0    3
            \
             4
 - - -

              7
           /     \
          5       8
         /  \       \
        1    6        9
       /  \
      0    3
           /  \
          2    4
