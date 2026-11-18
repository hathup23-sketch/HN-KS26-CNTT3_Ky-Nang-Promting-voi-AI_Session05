## 4.2. Trích xuất tin nhắn đặt vé ra JSON

**KET QUA AI**

```text
[
  {
    "ma_goi": "SVT",
    "ngay_su_kien": "2026-12-20",
    "nguoi_lon": 2,
    "tre_em": 1,
    "loai_ve": "thuong",
    "ghi_chu": null
  },
  {
    "ma_goi": "FZ",
    "ngay_su_kien": "2027-01-05",
    "nguoi_lon": 3,
    "tre_em": 0,
    "loai_ve": "thuong",
    "ghi_chu": "hỗ trợ xe lăn"
  },
  {
    "ma_goi": "VIP",
    "ngay_su_kien": null,
    "nguoi_lon": 4,
    "tre_em": 0,
    "loai_ve": "vip",
    "ghi_chu": "hỗ trợ tìm chỗ cho người khiếm thị"
  }
]
```

**Link trò chuyện:**https://share.gemini.google/ypJUKxYz0N4g

## 4.3. Báo giá vé bằng Chain-of-Thought

**KET QUA AI**

```text
Các bước tính toán chi tiết
Tiền người lớn:
Gói SVT có giá 1.200.000 đồng/người lớn, nhóm có 5 người lớn.
Phép tính: 
5
×
1.200.00
=
6.000.00
 đồng.
Tiền trẻ em:
2 trẻ em (8 tuổi và 10 tuổi) thuộc độ tuổi từ 5 đến 11 tuổi nên tính 70% giá vé người lớn.
1 bé 3 tuổi thuộc diện dưới 5 tuổi nên được miễn phí (0 đồng).
Phép tính: 
(
2
×
1.200.000
×
70
%
)
+
(
1
×
0
)
=
1.680.000
 đồng.
Tiền vé (trước giảm giá):
Tổng cộng tiền vé của người lớn và trẻ em.
Phép tính: 
6.000.00
+
1.680.00
=
7.680.00
 đồng.
Giảm giá nhóm:
Nhóm có đủ 5 người lớn nên được giảm 5% trên tổng tiền vé.
Mức giảm giá: 
7.680.000
×
5
%
=
384.000
 đồng.
Tiền vé sau giảm giá: 
7.680.00
−
384.000
=
7.296.00
 đồng.
Phụ thu:
Có 1 người lớn chọn khu ghế ưu tiên với mức phụ thu 300.000 đồng/người (không áp dụng giảm giá).
Phép tính: 
1
×
300.000
=
300.000
 đồng.
Tổng tiền:
Cộng tiền vé sau giảm giá và tiền phụ thu.
Phép tính: 
7.296.00
+
300.000
=
7.596.00
 đồng.
[RESULT: 7.596.000 đồng]
```

**Link trò chuyện:**https://share.gemini.google/DX9dZwxm3TzP

### b) Kiểm tra kết quả AI

AI đã trả lời đúng hết các bước theo yêu cầu đề bài và câu cuối cùng đã chốt đc [RESULT: <tổng tiền> đồng].

## 4.4. Dây chuyền xử lý khiếu nại – kết quả Trạm 1

**KET QUA AI**

```text
{
  "loai_su_co": "sai_khu_vuc",
  "so_khach": 2,
  "so_hiep_bi_anh_huong": 2,
  "tom_tat": "Khán giả mua vé gói SVT (2 người lớn) bị xếp sang khu không có mái che trong 2 hiệp đầu dù cam kết có mái che, gặp trời mưa và ghế ướt."
}
```

**Link trò chuyện:**https://share.gemini.google/CCfwm64TH9NX
