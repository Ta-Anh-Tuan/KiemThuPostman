# Kiểm Thử Postman

# API được chọn 
API được chọn là HTTP Cats, api cung cấp hình ảnh mèo

# Phân tích API
API: https://http.cat
Phương thức: GET
Tham số bắt buộc: id (mã số hình ảnh)

# Các trường hợp kiểm thử:
# TH1: truy vấn hợp lệ
GET: https://http.cat/300
Kết quả: Mã trạng thái 200 và ảnh tương ứng với id
![image](https://github.com/Ta-Anh-Tuan/KiemThuPostman/assets/96875304/e47662d3-f6b7-4aab-b234-be9555bc0e6e)


# TH2: truy vấn không hợp lệ
GET: https://http.cat/none
Kết quả: Mã trạng thái 404 và thông báo Not Found
![image](https://github.com/Ta-Anh-Tuan/KiemThuPostman/assets/96875304/a8d4fcfd-7b62-4db1-a1e8-45c76d923cb0)

# POST, PUT, DELETE
Kết quả: Failed vì không được cấp phép
![image](https://github.com/Ta-Anh-Tuan/KiemThuPostman/assets/96875304/c58411f0-c74c-406d-bac4-db4c184bd27d)
