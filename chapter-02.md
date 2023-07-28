
## 2.1 Nguyên lý mã hóa dự đoán DPCM

*Nguyên lý mã hóa dự đoán DPCM*

DPCM là phương pháp lượng tử hóa biên độ mẫu tín hiệu số thành mã nhị phân

- Differential: Thay vì mã hóa toàn bộ giá trị tín hiệu, chúng ta tính sai khác giữa các giá trị gần nhau để 
- Code: Biểu diễn các giá trị được thu nhận từ quá trình thành các giá trị nhị phân
- Modulation: Coi một đoạn giá trị của tín hiệu liên tục là một xung/một mẫu

## 2.4 Mã hóa dự đoán DPCM phù hợp với dữ liệu nào để đạt tỷ số nén cao? Độ tổn hao DPCM phụ thuộc vào điều kiện gì? Tính tỷ số nén với ví dụ cụ thể

*Mã hóa dự đoán DPCM phù hợp với dữ liệu nào để đạt tỷ số nén cao?*

Phù hợp với tín hiệu có giá trị mẫu có độ tương quan lớn, mỗi quan hệ với nhau (hàm tương quan), thường là các giá trị gần bằng nhau, không phải là các giá trị ngẫu nhiên.

*Tại sao DPCM trong mã hóa JPEG thành phần DC dùng vòng mở thì không gây tổn hao, trong khi mã hóa tiếng nói cần sử dụng DPCM với sơ đồ vòng đóng với bộ dự đoán tuyến tính?*

Trong JPEG, các giá trị đã được lượng tử hóa trước khi vào khối dự đoán, do đó không gây tổn hao tích lũy khi dùng bộ lượng tử hóa
Tín hiệu tiếng nói cần sử dụng nhiều mẫu liên tục để có thể cho chất lượng nén tốt
