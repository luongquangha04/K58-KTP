# K58-KTP
Bài tập 2 k225480106010  Lương Quang Hà môn HQT CSDL

## ĐIỀU KIỆN: (ĐÃ LÀM XONG BÀI 1)
1. Đã cài đặt SQL Server 2022 Dev.
2. Đã cài đặt SQL Managerment Studio bản mới nhất.
3. Đã kết nối từ SQL Managerment Studio vào SQL Server.
4. Đã có tài khoản github, biết cách tạo repository(kho lưu trữ) cho phép truy cập public.

## BÀI TOÁN:
- Tạo csdl quan hệ với tên QLSV gồm các bảng sau:
  + SinhVien(#masv,hoten,NgaySinh)
  + Lop(#maLop,tenLop)
  + GVCN(#@maLop,#@magv,#HK)
  + LopSV(#@maLop,#@maSV,ChucVu)
  + GiaoVien(#magv,hoten,NgaySinh,@maBM)
  + BoMon(#MaBM,tenBM,@maKhoa)
  + Khoa(#maKhoa,tenKhoa)
  + MonHoc(#mamon,Tenmon,STC)
  + LopHP(#maLopHP,TenLopHP,HK,@maMon,@maGV)
  + DKMH(#@maLopHP,#@maSV,DiemTP,DiemThi,PhanTramThi)

## YÊU CẦU:
1. Thực hiện các hành động sau trên giao diện đồ hoạ để tạo cơ sở dữ liệu cho bài toán:
  + Tạo database mới, mô tả các tham số(nếu có) trong quá trình.
  + Tạo các bảng dữ liệu với các trường như mô tả, chọn kiểu dữ liệu phù hợp với thực tế (tự tìm hiểu)
  + Mỗi bảng cần thiết lập PK, FK(s) và CK(s) nếu cần thiết. (chú ý dấu # và @: # là chỉ PK, @ chỉ FK)
2. Chuyển các thao tác đồ hoạ trên thành lệnh SQL tương đương. lưu tất cả các lệnh SQL trong file: Script_DML.sql
## Hình ảnh
![image](https://github.com/user-attachments/assets/aadf1a86-bfd7-4e2c-afb5-daa21aa88224)
![image](https://github.com/user-attachments/assets/8a7ee6dc-38a1-42da-94f9-e233abbe4edf)
![image](https://github.com/user-attachments/assets/bf27cedb-c830-4142-be00-165448c664a5)
![image](https://github.com/user-attachments/assets/5b934dce-d224-4c6f-9444-0ca58e03221d)
![image](https://github.com/user-attachments/assets/03a96d8d-d5a2-449a-b2ee-74dc10fedeed)
![image](https://github.com/user-attachments/assets/8b0d4d93-f2ee-49f3-affa-e4df1a69a6ea)
![image](https://github.com/user-attachments/assets/3e4bc7f2-bec1-4273-974e-e957628abed0)
![image](https://github.com/user-attachments/assets/71004135-2476-4e97-8646-5d124cd5fb0e)
![image](https://github.com/user-attachments/assets/2bab1fff-918d-493f-a309-c0674cd43fb2)
![image](https://github.com/user-attachments/assets/a91e16bd-3752-4d8e-8fef-eff325a188ef)
![image](https://github.com/user-attachments/assets/6d7d9499-f343-465b-a622-cd56b5cc578e)
![image](https://github.com/user-attachments/assets/70bb301d-ac1b-47dd-98cf-21acebb3b04c)
![image](https://github.com/user-attachments/assets/4f8b4d43-a941-47ee-8e44-e6bafc94e1d9)
![image](https://github.com/user-attachments/assets/7bbf787e-fdaa-4797-90eb-37706ca2761b)
![image](https://github.com/user-attachments/assets/5c45b8b7-90ef-4b9d-b979-8619dc307b0d)
![image](https://github.com/user-attachments/assets/e075dfaf-ca45-4861-bcbb-f2f73f5c14bd)
![image](https://github.com/user-attachments/assets/92d6b471-9acc-4b11-a106-fc126af426d9)
![image](https://github.com/user-attachments/assets/6ace7087-e0cd-4e4d-b81f-ad0897e4b66d)
![image](https://github.com/user-attachments/assets/a437d1f3-a43d-44d9-89a8-98f5d4eb7b80)
![image](https://github.com/user-attachments/assets/ddcfd09d-4db2-4e88-a9d4-635023790a60)
![image](https://github.com/user-attachments/assets/d0db75ae-af56-438b-96ad-49e3034433dc)
![image](https://github.com/user-attachments/assets/22b705ab-6c32-4a5c-9003-bc56f9f0e9f9)
![image](https://github.com/user-attachments/assets/bbabab72-f235-4385-ad87-332c22d4c125)

