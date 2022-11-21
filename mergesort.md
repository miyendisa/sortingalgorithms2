 >**1. [16,21,11,8,12,22]  dizisinin Merge Sort türüne göre aşamalarını yazınız.**
- Liste, her bir adımda daha küçük parçalara ayrılır ve tek eleman kalana kadar bu işlem tekrarlanır. Ardından birleştirilip sıralı liste oluşturulur.
- Öncelikle dizinin atomik birimlerine ulaşana kadar parçalama işlemine devam edelim.
  
                          [16,21,11,8,12,22]
 
                  [16,21,11]              [8,12,22]      

                 [16]  [21,11]           [8]  [12,22]

                [16]   [21] [11]        [8]   [12] [22]

* Dizi en küçük birimlere kadar parçalandıktan sonra, elemanların büyüklüklerine göre kıyaslayarak diziyi birleştirelim.

               [16]   [21] [11]          [8]   [12] [22]

                [16]   [11,21]            [8]   [12,22]    

                  [11,16,21]                [8,12,22]
* Son birleştirmeyle birlikte listenin sıralı hali aşağıdaki gibidir:   
  
          [8,11,12,16,21,22]
---

> **2. Big-O gösterimini yazınız.**

n terimli bir dizi için Big-O Notation;
 
$2^x=n$ 

$logn=x$

O (nlogn)
