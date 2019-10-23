# ruby_study

## Bài tập

### Bài 1. Tính toán và đầu ra BMI của các người sau (BMI = Weight[kg] / Height[m] / Height[m]).

Filename: 01_bmi.rb

|Name|Height[cm]|Weight[kg]|
|---|---|---|
|Mike|170|65|
|Bob|175|95|
|Ana|155|42|

```
Mike's BMI is 22.491349480968857
Bob's BMI is 31.020408163265305
Ana's BMI is 17.48178980228928
```

### Bài 2. Theo giá trị BMI, thêm thể loại của BMI như sau vào đầu ra của bài 1.

Filename: 02_bmi_with_category.rb

|BMI|Category|
|---|---|
|bmi > 18.5|Low|
|18.5 >= bmi > 25.0|Normal|
|25.0 >= bmi|Obese|

```
Mike's BMI is 22.491349480968857, category is Normal
Bob's BMI is 31.020408163265305, category is Obese
Ana's BMI is 17.48178980228928, category is Low
```
### Bài 3. Tính toán và đầu ra tống các số từ 1 đến 9876

Filename: 03_sum_1-9876.rb

```
48772626
```

### Bài 4. Đầu ra các số Fibonacci đến 10000

Xem: [https://vi.wikipedia.org/wiki/Dãy_Fibonacci](https://vi.wikipedia.org/wiki/D%C3%A3y_Fibonacci)  
Filename: 04_fibonacci.rb

```
0
1
1
2
3
5
8
13
21
34
55
89
144
233
377
610
987
1597
2584
4181
6765
```

### Bài 5. In ra các số từ 1 đến 100, nhưng mà nếu các số là

- bội của 3 thì in ra "Fizz"
- bội của 5 thì in ra "Buzz"
- bội của 15 thì in ra "FizzBuzz"

Filename: 05_fizzbuzz.rb

```
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17
Fizz
19
Buzz
Fizz
22
23
Fizz
Buzz
26
Fizz
28
29
FizzBuzz
31
32
Fizz
34
Buzz
Fizz
37
38
Fizz
Buzz
41
Fizz
43
44
FizzBuzz
46
47
Fizz
49
Buzz
Fizz
52
53
Fizz
Buzz
56
Fizz
58
59
FizzBuzz
61
62
Fizz
64
Buzz
Fizz
67
68
Fizz
Buzz
71
Fizz
73
74
FizzBuzz
76
77
Fizz
79
Buzz
Fizz
82
83
Fizz
Buzz
86
Fizz
88
89
FizzBuzz
91
92
Fizz
94
Buzz
Fizz
97
98
Fizz
Buzz
```

### Bài 6. Đầu ra các số ngày của mỗi tháng. Thêm vào mã nguồn dưới và cần sử dụng vòng lập.

Filename: 06_days_in_each_month.rb

```ruby
# 06_days_in_each_month.rb

month_names = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"]
days = [31, 29, 31, 30, 31, 30, 31, 31, 30, 31, 30, 31]

# Write here
```

```
January has 31 days
February has 29 days
March has 31 days
April has 30 days
May has 31 days
June has 30 days
July has 31 days
August has 31 days
September has 30 days
October has 31 days
November has 30 days
December has 31 days
```

### Bài 7. Sử dụng biến "dictonary" để dịch từ từ vựng tiếng Anh được nhập từ keyboard ra tiếng Việt. Nếu có từ vựng đó trong "dictionary" thì đầu ra từ vựng tiếng Việt đó. Nếu không có thì đầu ra "Not found".
Đẩu ra từ vựng tiếng Việt 

Filename: 07_dictionary.rb

```ruby
# 07_dictionary.rb

# Make dictionary
dictionary = {"apple" => "táo", "orange" => "cam", "grape" => "nho", "banana" => "chuối"}

# Receive input
puts "Input a word"
english_word = gets.chomp

# Write here
```

```
(Example 1)
Input a word
>> apple
apple is táo

(Example 2)
Input a word
>> durian
Not found
```

### Bài 8. Sắp xếp mảng biến "array_before_sorting" theo theo thứ tự tăng dần và đầu ra đó. Thêm vào mã nguồn dưới.

Filename: 08_sort_array.rb

```ruby
# 08_sort_array.rb

# Initialize Array (elements are random numbers from 0 to 999)
# see: https://docs.ruby-lang.org/en/master/Kernel.html#method-i-rand
array_before_sorting = []
10.times do
  array_before_sorting << rand(1000)
end

# Output array elements before 
# see: https://docs.ruby-lang.org/en/master/Array.html#method-i-join
before_sorting_str = array_before_sorting.join(", ")
puts "Before sorting: #{before_sorting_str}"

# Write here
```
```
(Example)
Before sorting: 240, 333, 363, 142, 575, 770, 460, 696, 863, 908
After sorting: 142, 240, 333, 363, 460, 575, 696, 770, 863, 908
```

### Bài 9. Đầu ra tổng số ngày vào thứ 7 và chủ nhật của "tháng này" (Kết quả đầu ra khác nhau tùy thuộc vào tháng thực thi chương trình này).

Xem: [https://docs.ruby-lang.org/en/master/Time.html](https://docs.ruby-lang.org/en/master/Time.html)  


Filename: 09_weekend_days.rb

```
(Example on Oct 2019)
Oct 2019 has 8 weekend days

(Example on Nov 2019)
Nov 2019 has 9 weekend days
```

