# Merge-Sort-Projesi

[16,21,11,8,12,22]

# Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

Sayıları tek kalana kadar ortan ikiye bölerek parçalıyoruz;

|[16,21,11] - [8,12,22]|

|[16,21] - [11]|    |[8,12] - [22]|

|[16] - [21]|    |[11]|    |[8] - [12]|    |[22]|

Küçük sayı solda kalacak şekilde tekrardan birleştiriyoruz;

|[16,21]| - |[11]|    |[8,12]| - |[22]|

|[11,16,21]| - |[8,12,22]|

|[8,11,12,16,21,22]|
______________________________________________________________

# Big-O gösterimini yazınız.

O(nlogn)
