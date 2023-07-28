**Thế nào là mã hóa VQ? Cơ sở lý thuyết và nguyên lý phương pháp VQ? Tại sao mã hóa theo phương pháp VQ cần 02 giai đoạn: (1) Pha huấn luyện (Learning Vector Quantization LVQ); (2) Pha mã hóa/Giải mã**

*Thế nào là mã hóa VQ?*

Ánh xạ một tập S gồm các vector k-chiều (vector gồm k thành phần) sang một tập S' gồm vector k-chiều khác. Số lượng các vector của S' nhỏ hơn số lượng các vector của S.

Tập S gồm các điểm dữ liệu trong không gian. Tìm các vector đại diện S' để mã hóa các điểm dữ liệu trong S. Mỗi vector trong S được đại diện bởi 1 vector trong S'

1. Biểu diễn các dữ liệu trong không gian 

*Tại sao mã hóa theo phương pháp VQ cần 02 giai đoạn: (1) Pha huấn luyện (Learning Vector Quantization LVQ); (2) Pha mã hóa/Giải mã*

Đầu vào: Bộ dữ liệu, mỗi dữ liệu x có k thành phần, là không gian dữ liệu k-chiều

Tìm:
- Số từ mã (số cụm & phân cụm - cluster)
- Vector đặc trungw rong cụm -> vector mã (code)

Không thể lựa chọn một cách ngẫu nhiên các thành phần trên từ bộ dữ liệu đầu vào. Do đó cần phải có *Pha huấn luyện* để tìm được để tìm được số cụm và vector mã phù hợp nhất.

