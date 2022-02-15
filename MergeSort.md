# Merge Sort Projesi Ödev

> [16,21,11,8,12,22] -> Merge Sort
> 
> ## Soru 1
> Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
> ``` 
> Çözüm:
> 1. [16,21,11,8,12,22]
> 2. [16,21,11] - [8,12,22]
> 3. [16] - [21,11]   -   [8,12] - [22]
> 4. [16] - [21] - [11]   -   [8] - [12] - [22]
> 5. [16] - [11,21]   -   [8,12] - [22]
> 6. [11,21,16] - [8,12,22]
> 7. [8,11,12,16,21,22]
> ```
> 
> ## Soru 2
> Big-O gösterimini yazınız.
> ``` 
> Çözüm:
> O(nlogn)
> ```