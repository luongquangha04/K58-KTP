## ÀI TẬP VỀ NHÀ 03 - MÔN HỆ QUẢN TRỊ CSDL:

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
sua bang dkmh vaf them bang diem
![image](https://github.com/user-attachments/assets/bddfcf40-2b4d-41b2-b796-1dfab04668be)

luu bai_tap_3schema
![image](https://github.com/user-attachments/assets/86a15445-afd6-449f-9ede-c4ae955f3e9d)

bang lien ket
![image](https://github.com/user-attachments/assets/901617cb-8f07-4f8c-95ba-f3446a23d1e7)

bang truy van
![Uploading image.png…]()



