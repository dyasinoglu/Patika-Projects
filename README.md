# Patika-Projects--Veri Yapıları ve Algoritmalar

## Project 1-Insertion Sort Project

 1)[22,27,16,2,18,6]--verilen dizi
 
 1.aşama--[2,27,16,22,18,6]-n
 2.aşama--[2,6,16,22,18,27]-(n-1)
 3.aşama--[2,6,16,18,22,27]-(n-2)
 
 2)Big O notaiton : n+(n-1)+(n-2)+1 =n.(n-1)/2 
 O(n^2)
 18 sayısı 3 aşamada ilk sırada bulunucağından Best Case e girer.
 
 [7,3,5,8,2,9,4,15,6]--dizisi
 1.adım-- [2,3,5,8,7,9,4,15,6]
 2.adım-- [2,3,4,8,7,9,5,15,6]
 3.adım-- [2,3,4,5,7,9,8,15,6]
 4.adım-- [2,3,4,5,6,9,8,15,7]
 
 ## Project 2-Merge Project
 
 [6,21,11,8,12,22]--verilen dizi
 
 1.adım-- [6,21,11]          [8,12,22]
 
 2.adım-- [6]  [21,11]      [8,12] [22]   
 
 3.adım--  [6,11,21]        [8,12,22]
 
 4.adım--  [6,8,11,12,21,22]
 
 Big O notaion:  O(nlogn)
 
 ## Porject 3-Binary Search Tree Project
 
 [7,5,1,8,3,6,0,9,4,2]
 
 Root 5 tir.  
 7 5'in sağında ve 1 5'in solundadır.
 8 7'in sağındadır ve 3 1'in sağındadır.
 6 7'nin solundadır ve 0 1'in solundadır.
 9 8'in sağındadır ve 4 3'ün sağındadır.
 2  3'ün solundadır
 
                root-->  5
                   1           7
                 0    3      6    8
                    2   4          9
                    
   [Pativa.Dev                 


