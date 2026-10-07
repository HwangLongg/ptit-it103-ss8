
lỗi
pop() lấy phần tử cuối nên sai thứ tự xe.
<= length làm vòng lặp chạy thêm 1 lần và lấy undefined.
undefined cộng vào số làm kết quả thành NaN.
test

trường hợp 1: mảng xe có 3 phần tử

dữ liệu: ['29A-112.33', '30E-889.12', '51K-678.99']

kết quả sai: 51K-678.99

kết quả đúng: 29A-112.33

trường hợp 2: mảng điện năng có 4 phần tử

dữ liệu: [45.2, 30.5, 62.8, 28.0]

kết quả sai: NaN

kết quả đúng: 166.5 kWh

trường hợp 3: mảng rỗng

dữ liệu: []

kết quả đúng: 0 kWh

trường hợp 4: mảng có 1 phần tử

dữ liệu: [20]

kết quả đúng: 20 kWh