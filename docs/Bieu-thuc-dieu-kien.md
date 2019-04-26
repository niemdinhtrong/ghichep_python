# Thực thi có điều kiện

## Biểu thức boolean

Biểu thức boolean là một biểu thức trả về hai giá trị là true hoặc false. 
VD biểu thức so sánh.

```
>>> 5 == 5
True
>>> 5 == 6
False
```

Giá trị `True` hoặc `False` có kiểu giá trị là `bool` chứ không phải `string`

```
>>> type(True)
<class 'bool'>
>>> type(False)
<class 'bool'>
```

Các phép so sánh

```
x == y
x != y
x > y
x < y
x >= y
x <= y
x is y
x is not y
```

Lưu ý: Với một dấu `=` thì được sử dụng để gán giá trị. Còn sử dụng hai dấu `==` thì sẽ được sử dụng để so sánh.

## Toán tử logic

Có 3 toán tử logic là: and, or, not. 

VD:

`x > 0 and a < 10`  Kết qủa trả về là `True` nếú giá trị của nằm trong khoảng 0< x < 10

`n%2 == 0 or n%3 == 0` trả về giá trị `True` nếu giá trị của n là 2 hoặc 3.

`not (x>y)` trả về giá trị `True` nếu (x>y) là sai <=> x nhỏ hơn y.

