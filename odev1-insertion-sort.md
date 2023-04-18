# Data Yapıları ve Algoritmalar 


## Odev 1 - Insertion Sort

### [22,27,16,2,18,6] -> Adımlar: 

* 22 ve 27 kıyasla 22 daha düşük doğru yerde.
* 27 ve 16 kıyasla : 16 daha düşük --> swapla --> yeni hali :[22,16,27,2,18,6]
* 22 ve 16 kıyasla :  16 daha düşük --> swapla --> yeni hali :[16,22,27,2,18,6]
* 27 ve 2 kıyasla : 2 daha düşük --> swapla --> yeni hali :[16,22,2,27,18,6]
* 22 ve 2 kıyasla : 2 daha düşük --> swapla --> yeni hali :[16,2,22,27,18,6]
* 16 ve 2 kıyasla : 2 daha düşük --> swapla --> yeni hali :[2,16,22,27,18,6]
* 27 ve 18 kıyasla : 18 daha düşük --> swapla --> yeni hali :[2,16,22,18,27,6]
* 22 ve 18 kıyasla : 18 daha düşük --> swapla --> yeni hali :[2,16,18,22,27,6]
* 16 ve 18 kıyasla : 16 daha düşük --> yeni hali :[2,16,18,22,27,6]
* 27 ve 6 kıyasla : 6 daha düşük --> swapla --> yeni hali :[2,16,18,22,6,27]
* 22 ve 6 kıyasla : 6 daha düşük --> swapla --> yeni hali :[2,16,18,6,22,27]
* 18 ve 6 kıyasla : 6 daha düşük --> swapla --> yeni hali :[2,16,6,18,22,27]
* 16 ve 6 kıyasla : 6 daha düşük --> swapla --> yeni hali :[2,6,16,18,22,27]
* Bitir. 
* SONUC: [2,6,16,18,22,27]
### big-O = O(n^2)
### Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız -->Cevap:  1. Average Case

### [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
* İlk elementi test etmek için Baştan sona hepsini döndür ve kıyasla hangisi en düşükse onla swapla --> [2,3,5,8,7,9,4,15,6] 
* İkinci elementi dene --> [2,3,8,7,9,4,15,6] Aynı kaldı değişmedi
* Üçümcü element için dene --> [2,3,4,8,7,9,5,15,6] 
* 4üncü için dene --> [2,3,4,5,7,9,8,15,6] 
* ....... O(logn)
