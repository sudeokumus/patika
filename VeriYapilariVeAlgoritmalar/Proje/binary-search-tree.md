# Binary Search Tree Projesi

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

---
Root: 7    
- 5, 7'den küçük olduğundan 7'nin soluna ekleriz.

##
                        7
                 5                         
##

- 1, 7'den ve 5'ten küçük olduğundan sola ekleriz.

##
                        7
                 5              
           1            
##

- 8, 7'den büyük olduğundan 7'nin sağına ekleriz.

##
                        7
                 5              8
          1            
##

- 3; 7'den ve 5'ten küçük, 1'den büyük olduğundan 1'in sağına ekleriz.

##
                        7
                 5              8
          1            
             3
##

- 6; 7'den küçük, 5'ten büyük olduğundan 5'in sağına ekleriz.

##
                        7
                 5              8
          1            6
             3
##

- 0; 7, 5 ve 1'den küçük olduğundan 1'in soluna ekleriz.

##
                        7
                 5              8
          1            6
        0    3
##

- 9, 7'den ve 8'den büyük olduğundan 8'in sağına ekleriz.

##
                        7
                 5              8
          1            6                 9
        0    3
##

- 4; 7 ve 5'ten küçük, 1 ve 3'ten büyük olduğundan 3'ün sağına ekleriz.

##
                        7
                 5              8
          1            6                 9
        0    3
               4
##

- 2; 7 ve 5'ten küçük, 1'den büyük ve 3'ten küçük olduğundan 3'ün soluna ekleriz.

##
                        7
                 5              8
          1            6                 9
        0    3
            2  4
##






