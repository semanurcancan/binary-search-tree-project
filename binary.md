# Proje 3
[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
### birinci aşama
- root:3 iken sağında 7 solunda 1 vardır
    - sub treede root:7iken sağında 8 solunda 5 vardır
        - sub treede root 8 ike sağında 9 vardır
        - sub treede root 5 iken sağında 6 solunda 4 vardır
    - sub treede root 1 iken sağında 2 solunda 0 vardır.

```
               3
             /    \
            1      7
          /  \     / \
         0    2   5   8
                /  \    \
               4    6    9


