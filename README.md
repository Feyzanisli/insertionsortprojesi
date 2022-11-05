# **Insertion Sort Projesi**
*[patika.dev profilim için tıklayınız.](https://app.patika.dev/feyzameyza)*

**[ 22, 27, 16, 2, 18, 6 ]** elemanlarının **videoda öğretildiği şekliyle** *(konu anlatımındaki kaynaklarda farklı şekilde anlatılıyor)* insertion sort algoritmasına göre diziliş aşamaları şöyledir:

1. **[ 2,** 27, 16, *22,* 18, 6 **]**
2. **[ 2, 6,** 16, 22, 18, *27* **]**
3. **[ 2, 6, 16,** 22, 18, 27 **]**
4. **[ 2, 6, 16, 18,** *22,* 27 **]**
5. **[ 2, 6, 16, 18, 22,** 27 **]**
6. **[ 2, 6, 16, 18, 22, 27 ]**

---
*Insertion sort'un kötü (elemanların ters dizildiği) senaryoda Big-O gösterimi;*
- n+(n-1)+(n-2)+(n-3)...+1, 
- yani n*(n+1)/2
- domine eden n^2 olduğundan
- **O(n^2)**'dir.

*İyi (elemanların sıralı dizildiği) senaryoda ise;*
- **O(n)**'dir.
---

Dizi sıralandıktan sonra 18 sayısı ''Average Case'' kapsamına girer.

---

**[ 7, 3, 5, 8, 2, 9, 4, 15, 6 ]** dizisinin ilk 4 adımı şöyledir:
1. **[ 2,** 3, 5, 8, *7,* 9, 4, 15, 6 **]**
2. **[ 2, 3,** 5, 8, 7, 9, 4, 15, 6 **]**
3. **[ 2, 3, 4,** 8, 7, 9, *5,* 15, 6 **]**
4. **[ 2, 3, 4, 5,**  7, 9, *8,* 15, 6 **]**

