# Patika Ödevim
## Insertion Sort : En basit sortin algoritmalarından biridir. Verilen örüntüye ait en küçük elemanı buluyor ve en baştaki sayı ile yer değiştiriyor. İkinci en küçük elemanı buluyor ve 2. sıra ile yer değiştiriyor. Baktın ki ikinci sıradaki eleman en küçük dokunma!!! Hemen 3. sıraya geç. 4, 5 derken dizi bitti. İşte insertion sort'un temel çalışma prensibi bu.

## Big-O Notation : Bir algoritmanın performansını ve time complexity'sini hesaplamak için kullanılır.

## Time Complexity : Bir algoritmanın çalışması için gerekli olan süredir. Ancak buradaki süre, saniyeleri hesaplayarak değil, kaç tane işlem gerçekleştirdiğine göre hesaplanmaktadır. Uygulama tarafından gerçekleştirilen işlem sayısı, veri setinin büyüklüğüne ve o veri setindeki elemanların sırasına göre belirlenir.

## [22,27,16,2,18,6] sayıları veriliyor. Bu sayıların insertion sortunu bulalım;

## Cevap :
* 2 ile 22 yer değiştirir. [2,27,16,22,18,6]
* 27 ile 6 yer değiştirir. [2,6,16,22,18,27]
* Sayı düzeni korunursa o bir sonraki dokunmadan diğerine geçilir.
* 22 ile 18 yer değiştirir. [2,6,16,18,22,27]
* 5 ve 6 sıradakiler düzene girdiyse değişim durur işlem sonlanır.

## Big O:  O(n²) = O(6²) = O(36).

## Time Complexity:
* Average case: Aradığımız sayının ortada olması,
* Worst case: Aradığımız sayının sonda olması,
* Best case: Aradığımız sayının dizinin en başında olması.

18 sayısı Average case kapsamına girer.

## [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.

* 7 ile 2 yer değiştirir. [2,3,5,8,7,9,4,15,6] 
* 3 e dokunma devam et.
* 5 ile 4 yer değiştirir.[2,3,4,8,7,9,5,15,6]
* 8 ile 5 yer değiştirir. [2,3,4,5,7,9,8,15,6] -> 4.adımı