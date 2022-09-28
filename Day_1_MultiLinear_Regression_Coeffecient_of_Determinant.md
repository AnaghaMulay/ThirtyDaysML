# ThirtyDaysML

Earlier, I was refering to the formula to determine this coeffecient of Determinant where both X and y variables' values are involved:

![image](https://user-images.githubusercontent.com/20473196/192806483-245d5279-3222-4b43-98a4-b84e33b657f6.png)

But in case of multilinear regregression, where more than one 'X' attributes are present, this formula does not work. So in such a case, we have to consider the formula where values of X are not involved, like the one below:
![image](https://user-images.githubusercontent.com/20473196/192807589-3fc575ac-afd4-4220-9c21-cccf0fe5aa99.png)

Here RSS stands for Residual squares' sum and TSS stands for Total sum of squares. 

![image](https://user-images.githubusercontent.com/20473196/192809204-3eeb1aa7-599d-4ce7-b91d-ac9b8577c0b1.png)

here f(xi) is the predicted value or y_pred and 

![image](https://user-images.githubusercontent.com/20473196/192811001-4bf0e753-39ef-462c-ac07-f5c6452749f9.png)

The problem statement is given on link https://machinehack.com/practices/coefficient-of-determination-c7a0b/description

