# Binary-Search-www.patika.dev
**[7, 5, 1, 8, 3, 6, 0, 9, 4, 2]** dizisinin Binary-Search-Tree aşamalarını yazınız.

**Cevap:**

**Root=5** seçildi.

**1.** 3<5 olduğu için 5'in soluna, 7>5 olduğu için 5'in sağına.

**2.** 1<3 olduğu için 3'ün soluna, 4>3 olduğun için 3'ün sağına.

**3.** 6<7 olduğu için 7'nin soluna, 8>7 olduğu için 7'nin sağına

**4.** 0<1 olduğu için 1'in soluna, 2>1 olduğu için 1'in sağına.

**5.** 9>8 olduğu için 8'in sağına.

```
                                 5
                               /   \
                              /     \
                             3       7
                            / \     / \
                           1    4  6   8
                          / \           \
                         0   2           9
``` 