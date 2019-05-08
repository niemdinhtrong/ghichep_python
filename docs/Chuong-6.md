# Chương 6: Strings

## String

String là một chuỗi ký tự liên tục. 

```
>>> fruit = 'banana'
>>> letter = fruit[1]
>>> print(letter)
a
```

Trong ví dụ trên biến `fruit` được gán một chuỗi `banana`. Tiếp theo đó ta gán ký tự thứ nhất trong biến `fruit` cho biến `letter`. Ta thấy biến `letter` lúc này có giá trị là `a`. Nhưng chúng ta lại thấy `b` mới là ký tự thứ nhất chứ không phải là giá trị `a`. Điều này là bởi vì trong Python quy định nó đánh số thứ tự từ 0 chứ không phải 1 là thứ tự đầu tiên.

```
>>> letter = fruit[0]
>>> print(letter)
b
```

## Get độ dài của chuỗi

Để lấy độ dài của chuỗi ta sử dụng function `len`

```
>>> fruit = 'banana'
>>> len(fruit)
6
```

