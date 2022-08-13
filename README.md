# BinarySearchTree_Project
Patika.dev veriyapıları project

**[7,5,1,8,3,6,0,9,4,2] dizisinin Binary-Tree aşamalarını yazınız.**  

| Açıklama |      |      |      |
| -------- | :--: | :--: | ---- |
| root=7   |      |  7   |      |
          
**5 sayısı 7'den küçük olduğu için 7'nin soluna ekledik**

| Açıklama             |      |      |      |      |      |
| :------------------- | :--: | :--: | :--: | ---- | ---- |
|                      |      |      |  7   |      |      |
|                      |      |  /   |      |      |      |
| sol tarafa 5 eklendi |  5   |      |      |      |      |

**1 sayısını 7 ve 5'ten küçük olduğundan dolayı 5'in soluna eklendi**

| Açıklama             |      |      |      |      |      |
| :------------------- | :--: | :--: | :--: | :--: | :--: |
|                      |      |      |      |      |  7   |
|                      |      |      |      |  /   |      |
|                      |      |      |  5   |      |      |
|                      |      |  /   |      |      |      |
| sol tarafa 1 eklendi |  1   |      |      |      |      |

**8 sayısı 7 den büyük olduğundan dolayı 7'nin sağına eklendi**

| Açıklama             |      |      |      |      |      |      |      |
| -------------------- | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|                      |      |      |      |      |  7   |      |      |
|                      |      |      |      |  /   |      |  \   |      |
| sağ tarafa 8 eklendi |      |      |  5   |      |      |      |  8   |
|                      |      |  /   |      |      |      |      |      |
|                      |  1   |      |      |      |      |      |      |

**3 sayısı 7'den küçük 1 den büyük olduğundan dolayı 1'in sağına eklendi**


| Açıklama             |      |      |      |      |      |      |      |
| -------------------- | :--: | ---- | ---- | :--: | :--: | :--: | :--: |
|                      |      |      |      |      |  7   |      |      |
|                      |      |      |      |  /   |      |  \   |      |
|                      |      |      | 5    |      |      |      |  8   |
|                      |      | /    |      |      |      |      |      |
|                      |  1   |      |      |      |      |      |      |
|                      |      | \    |      |      |      |      |      |
| sağ tarafa 3 eklendi |      |      | 3    |      |      |      |      


**6 sayısı 7'den küçük 5 den büyük olduğundan dolayı 5'in sağına eklendi**

| Açıklama             |      |      |      |      |      |      |      |
| -------------------- | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|                      |      |      |      |      |  7   |      |      |
|                      |      |      |      |  /   |      |  \   |      |
|                      |      |      |  5   |      |      |      |  8   |
|                      |      |  /   |      |  \   |      |      |      |
| sağ tarafa 6 eklendi |  1   |      |      |      |  6   |      |      |
|                      |      |  \   |      |      |      |      |      |
|                      |      |      |  3   |      |      |      |      |



**0 sayısı 7,5,1 den küçük olduğundan dolayı sola eklendi**

| Açıklama             |      |      |      |      |      |      |      |      |      |
| -------------------- | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|                      |      |      |      |      |      |      |  7   |      |      |
|                      |      |      |      |      |      |  /   |      |  \   |      |
|                      |      |      |      |      |  5   |      |      |      |  8   |
|                      |      |      |      |  /   |      |  \   |      |      |      |
|                      |      |      |  1   |      |      |      |  6   |      |      |
|                      |      |  /   |      |  \   |      |      |      |      |      |
| sol tarafa 0 eklendi |  0   |      |      |      |  3   |      |      |      |      |



**9 sayısı 7 den büyük olduğundan dolayı sağa eklendi**

| Açıklama             |      |      |      |      |      |      |      |      |      |      |      |
| -------------------- | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|                      |      |      |      |      |      |      |  7   |      |      |      |      |
|                      |      |      |      |      |      |  /   |      |  \   |      |      |      |
|                      |      |      |      |      |  5   |      |      |      |  8   |      |      |
|                      |      |      |      |  /   |      |  \   |      |      |      |  \   |      |
|                      |      |      |  1   |      |      |      |  6   |      |      |      |  9   |
|                      |      |  /   |      |  \   |      |      |      |      |      |      |      |
| sol tarafa 0 eklendi |  0   |      |      |      |  3   |      |      |      |      |      |      |


**4 sayısı 7,5 den küçük 3 den büyük olduğundan sağa eklendi**



**2 sayısı 7,5,3 den küçük olduğundan sola eklendi**



