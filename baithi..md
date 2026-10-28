# BÀI LÀM – HACKATHON 01

- **Mã đề:** 14
- **Họ tên:Nguyễn Trọng Nhân 7
- **Lớp:CNTT2
- **Link repository:https://github.com/tnhan288/HCM_KS26_CNTT2_CNTT2_Nhap-Mon-CNTT_Hackathon01
- **Hệ điều hành (Windows/macOS):Window

## 4.2. Thao tác máy tính cơ bản bằng CLI

get-location
get-childitem -force
Move-Item .\huong_dan_cham_soc.txt .\docs\
Move-Item .\logo_nha_khoa.png .\media\
copy-item .\media\Logo_Nha_khoa.PNG .\backup\
remove-item .\temp_226.tmp
set-location .\logs
Get-childitem
Set-location ..


### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/28/2026   2:03 PM                backup
d-----        10/28/2026   2:06 PM                data
d-----        10/28/2026   2:03 PM                docs
d-----        10/28/2026   2:06 PM                logs
d-----        10/28/2026   2:03 PM                media
d-----        10/28/2026   2:02 PM                starter-kit


```

## 4.3. Lọc log thủ công

### Lệnh đã chạy

```shell
 get-childitem -filter *.log -r | select-String "ERROR"
```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text

logs\Clinic.log.log:9:2026-04-28 09:51:29 [ERROR] Ket noi he thong ho so that bai
logs\Clinic.log.log:13:2026-04-28 10:07:29 [ERROR] Khong tim thay trang /bang-gia-dich-vu (404)
logs\Clinic.log.log:16:2026-04-28 10:19:29 [ERROR] Ket noi he thong ho so that bai
logs\Clinic.log.log:18:2026-04-28 10:27:29 [ERROR] Ket noi he thong ho so that bai
logs\Clinic.log.log:20:2026-04-28 10:35:29 [ERROR] Dat lich hen that bai

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [ ] Heading 1: tên dự án
- [ ] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh
(get-childitem -filter *.log -r | select-String "ERROR")
```shell


```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
5

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/dieu_tri_thang_4.xlsx`, không cần ghi vào đây.
