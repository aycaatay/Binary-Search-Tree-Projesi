# Binary-Search-Tree-Projesi
# [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.
# Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.
# ÇÖZÜM:
# Root=7; sayıları sırası ile küçüktür büyüktür karşılaştırmasına göre sola veya sağ tarafa yazarız.
# # 5<7 ise sola yazılır.
# 1<5,7 ise 5in soluna yazılır
# 7<8 ise 7nin sağına yazılır
# 1<3<5,7 ise 1in sağına yazılır
# 5<6<7 ise 5in sağına yazılır
# 0<1 ise 1in soluna yazılır.
# 7,8<9 ise 8in sağına yazılır.
# 3<4<5,7 ise 3ün sağına yazılır.
# 1<2<3,5,7 ise 3ün soluna yazılır.

           7
        5     8
      1    6      9
    0    3
       2   4
      

# şeklinde ifade edilebilir.
# https://www.patika.dev/tr
