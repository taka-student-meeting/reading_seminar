### Định nghĩa Machine Learning

### Supervised Learning & Unsupervised Learning

|               | Supervised Learning   | Unsupervised Learning  |
| ------------- |:-------------:|:-----:|
| Input data    | (Feature, Label) | (Feature) |
| Output data   | f(x) -> y     |  Tuỳ thuộc vào bài toán |
| Cách đánh giá | Độ chính xác      | Tuỳ thuộc vào bài toán |
|               | Prediction (Regression)      | Clustering |
| Các loại      | Classification      | Topic Modeling |
|               |                     | Features Learning (PCA, SVD, NMF) |
| Discussion    | Cần dán nhãn cho dữ liệu -> tốn thời gian, công sức | Có triển vọng phát triển trong tương lai? |

### Linear Regression (hồi quy tuyến tính)
Với một tập dữ liệu đầu vào bao gồm (feature x, label y), cần học được 1 hàm y=h(x) để biểu diễn dữ liệu đầu vào.
Trong trường hợp linear regression, hàm h(x) là tuyến tính. ![](http://mathurl.com/hzs2x7v.png?raw=true) => việc cần làm là tìm ra ![](http://mathurl.com/glcmjrz.png?raw=true)

Đánh giá hàm h(x) là tốt hay không dựa vào cost function ![](http://mathurl.com/hn28ok9.png?raw=true) => tìm ![](http://mathurl.com/glcmjrz.png?raw=true) để cost function có giá trị trung bình nhỏ nhất.

-> Cách tìm ![](http://mathurl.com/glcmjrz.png?raw=true) chính là contribution của bài báo.

Các bước khi nghiên cứu 1 bài toán linear regression:

Chọn dữ liệu -> chọn hàm h(x) (cách làm mang tính heuristic nhưng ko bị cứng nhắc) -> tìm ![](http://mathurl.com/glcmjrz.png?raw=true) (main contribution)

### Giới thiệu 1 số tool hữu ích

scikit_learn: thư viện python có sẵn 1 số function machine learning

jupyter: tool lập trình tương tác
