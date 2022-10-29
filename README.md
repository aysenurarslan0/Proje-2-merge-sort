# Proje-2-merge-sort
1 [Patika.dev] (http://www.patika.dev/tr)


##[16,21,11,8,12,22]-> merge sort
  
  Yukardaki dizinin sort türüne göre aşamalarını yazınız.

  [16,21,11,8,12,22] yapı ikiye bölünür
     
    [16,21,11].   [8,12,22]
Tekrar bölüyoruz
  
   [16] [21,11]   [8]
   [12,22] tek kalması için tekrar bölüyoruz 
    
   [16] [21] [11] [8] [12]
   [22] Bu yapıyı tekrar kademeli olarak birleşiyoruz.

    [16]  [11,21]   [8]
      
     [12,22] Bu diziyi tekrar sıralı olarak birleştiriyoruz.
     

     [11,16,21]    [8,12,22]
      
Son birleştirme işlerini gerçekleştiriyoruz
     
        [8,11,12,16,21,22]
   ## Big-O gösterimini yazınız.
       -O(nlogn)

