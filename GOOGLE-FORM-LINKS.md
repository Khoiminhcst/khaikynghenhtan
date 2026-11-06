# Google Form đặt hàng – Khởi Minh Gifts (DÙNG CHUNG cho trang rắn và trang ngựa)

Tài khoản sở hữu: khoiminhcst.vn@gmail.com

- **Link gửi khách (viewform):** https://docs.google.com/forms/d/e/1FAIpQLScIZNYqrPQ8m9MQVsgGD02DwPnDymnuc5C3HsA1DYKbNrxYmw/viewform
- **Link chỉnh sửa form:** https://docs.google.com/forms/d/16FOA4Qju1qdNKsIydqIqu98SukGQIMihDCRy1QjNcyI/edit
- **Sheet kết quả (đơn khách):** https://docs.google.com/spreadsheets/d/1XDNPAD2mTgLBpwoPZgO2CXBgds_DAybIN02juEYO7U0/edit

## Nối với website (phần `GFORM_URL` và `GFORM_FIELDS` trong index.html của cả hai trang)
Website gửi đơn ngầm vào form qua `.../formResponse`. Mã trường hiện tại:

| Câu hỏi | Mã trường |
|---|---|
| Họ và tên | entry.298093093 |
| Số điện thoại | entry.1606485930 |
| Email | entry.1583471348 |
| Tên công ty | entry.1855727194 |
| Sản phẩm đặt mua | entry.638326445 |
| Số lượng | entry.232570124 |
| Địa chỉ nhận hàng | entry.1006662555 |
| Ngày cần nhận hàng | entry.1359979500 (chưa dùng) |
| Ghi chú | entry.98961114 |

Nếu tạo lại form hoặc thêm/xóa/đổi câu hỏi thì mã trường đổi: cập nhật lại `GFORM_URL` và `GFORM_FIELDS` ở cả hai trang.

Email xác nhận: file `XacNhanEmail.gs` dán trong Trình chỉnh sửa tập lệnh của form, `FORM_ID` = 16FOA4Qju1qdNKsIydqIqu98SukGQIMihDCRy1QjNcyI.
