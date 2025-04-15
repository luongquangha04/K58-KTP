## BÀI TẬP VỀ NHÀ 02- 03 - MÔN HỆ QUẢN TRỊ CSDL:

## DEADLINE: 23H59 NGÀY 30/03/2025

## ĐIỀU KIỆN: (ĐÃ LÀM XONG BÀI 2)

# BÀI TOÁN: Sửa bài 2 để có csdl như sau:
  + SinhVien(#masv,hoten,NgaySinh)
  + Lop(#maLop,tenLop)
  + GVCN(#@maLop,#@magv,#HK)
  + LopSV(#@maLop,#@maSV,ChucVu)
  + GiaoVien(#magv,hoten,NgaySinh,@maBM)
  + BoMon(#MaBM,tenBM,@maKhoa)
  + Khoa(#maKhoa,tenKhoa)
  + MonHoc(#mamon,Tenmon,STC)
  + LopHP(#maLopHP,TenLopHP,HK,@maMon,@maGV)
  + DKMH(#id_dk, @maLopHP,@maSV,DiemThi,PhanTramThi)
  + Diem(#id, @id_dk, diem)

# YÊU CẦU:
1. Sửa bảng DKMH và bảng Điểm từ bài tập 2 để có các bảng như yêu cầu.
2. Nhập dữ liệu demo cho các bảng (nhập có kiểm soát từ tính năng Edit trên UI của mssm)
3. Viết lệnh truy vấn để: Tính được điểm thành phần của 1 sinh viên đang học tại 1 lớp học phần.

# hinh anh paste
tao bang giao vien chu nhiem
![Screenshot 2025-03-22 192029](https://github.com/user-attachments/assets/4a164fa9-e406-4891-8391-7a8862a7eed7)

tao bang khoa
![Screenshot 2025-03-24 040210](https://github.com/user-attachments/assets/dfbeff6b-7ccc-4291-9f4c-a0ac3d16c8a9)

tao bang giao vien
![Screenshot 2025-03-24 041547](https://github.com/user-attachments/assets/90f9f68c-cdd9-4730-84a0-079d49be3906)

tao bang lop
![Screenshot 2025-03-24 041547](https://github.com/user-attachments/assets/99913285-0eff-45d7-a3cc-61e57ab7aae0)

tao bang sinh vien
![Screenshot 2025-03-24 041547](https://github.com/user-attachments/assets/c37dea0b-3f85-4ea8-9ad4-0534817bddfb)

tao bang dang ki mon hoc
![Screenshot 2025-03-24 041923](https://github.com/user-attachments/assets/1f498e78-55d7-442a-a22a-e5e85e1af0ab)

bang thong tin
![Screenshot 2025-03-24 043248](https://github.com/user-attachments/assets/93496c00-f9f7-40c3-b684-bb3ca5fbe99a)


sua bang dkmh va them bang diem
![image](https://github.com/user-attachments/assets/bddfcf40-2b4d-41b2-b796-1dfab04668be)

luu bai_tap_3schema
![image](https://github.com/user-attachments/assets/86a15445-afd6-449f-9ede-c4ae955f3e9d)

bang lien ket
![image](https://github.com/user-attachments/assets/901617cb-8f07-4f8c-95ba-f3446a23d1e7)

bang truy van
![Uploading image.png…]()



