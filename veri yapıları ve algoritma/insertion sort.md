## Insertion Sort
### Verilen dizi: [22,27,16,2,18,6]
Insertion Sort her adımda bir ögeyi sıralı hale getirir.

* 1.Adım: 27,22 den büyük yani yerinde kalır.

        [22,27,16,2,18,6]

* 2.Adım: 16,27 den küçük yani yer değiştirir. 16,22 den küçük yer değiştirir. 

        [16,22,27,2,18,6]
* 3.Adım: 2, 27 22 ve 16 dan küçük yani en başa gelir.

        [2,16,22,27,18,6]         
* 4.Adım: 18, 27 den 22 den küçük ve 16 ve 2 den büyük.

        [2,16,18,22,27,6]    
* 5.Adım: 6, 27 22 18 ve 16 dan küçük 2 den büyük.

        [2,6,16,18,22,27]  

Worst Case : O(n²) 

Best Case : O(n)

Average Case : O(n²) 

18 sayısı ortadadır.(3. index) Average Case'e girer.

## Selection Sort
### Verilen dizi: [7,3,5,8,2,9,4,15,6]

* 1.Adım : En küçük 2, 0.index ile yer değiştirir.

        [2,3,5,8,7,9,4,15,6]
* 2.Adım : 1. index ve sonrası [3,5,8,9,4,15,6]
En küçük 3,yerinde kalır. 

        [2,3,5,8,7,9,4,15,6]
* 3.Adım : 2. index ve sonrası [5,8,7,9,4,15,6]
En küçük 4,2. inkex ile yer değiştirir.

        [2,3,4,8,7,9,5,15,6]
* 4.Adım : 3. index ve sonrası [8,7,9,5,15,6]
En küçük: 5,3. index ile yer değiştirir.

        [2,3,4,5,7,9,8,15,6]
...




