
## Mô hình nguyên lý phân tích tín hiệu thành các tín hiệu dải tần con (subband) và các ký thuật cơ sở (sampling, downsampling, linear filter/digital filter, filter bank,...)

Chỉ cần hiểu mô hình. Từ mô hình lý thuyết ra 2 kiểu sơ đồ nguyên lý
Bỏ thuật toán chi tiết câu 4,5, chỉ cần mô tả luồng hoạt động
Lấy tín hiệu thì bộ lọc thông thấp rất quan trọng do năng lượng tập trung ở tần số thấp → cần chia kĩ
Thông cao chỉ cần chia vừa phải → do đó có hình chữ U

Lọc thông dải, mỗi bộ lọc có 1 dải tần, lọc đòng thời 32 bộ lọc
Đầu vào đưa cách điểm 32 tín hiệu → tương đương downsampling

Phép biến đổi wavelet là biến đổi miền tần sau, hiểu miêu tả hoạt động, không yêu cầu chi tiết thuật toán

*Thế nào là bộ lọc số/bộ lọc tuyển tính/bộ lọc H*



*Thế nào là phép tích chập*



*Thế nào là lấy mẫu tín hiệu số/sampling*


## Thuật toán mã hóa dải tần con (Coding) có đặc điểm thế nào?

Nằm đằng sau bộ mã hóa tín hiệu phân tích bao gồm 2 phần mã hóa từng ảnh và mã hóa cây dữ liệu đối với ảnh, đối với âm thanh thì mã hóa đồng thời 32 tín hiệu dải tần con

## Hai kiểu sơ đồ phân tích

Hai kiểu

Dựa vào băng lọc thông thấp thông cao
Số tầng và số nhanh do người thiết kế quyết định

Dựa vào M bộ lọc thông dải
Âm thanh dải song song