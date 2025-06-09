# baitapthuchanh-python
# Bài tập thực hành python
Bài 1: 
Thực hiện lấy dữ liệu thời tiết từ url sau: https://api.open-meteo.com/v1/forecast?latitude=52.52&longitude=13.41&past_days=10&hourly=temperature_2m,relative_humidity_2m,wind_speed_10m
Yêu cầu:
+ Lấy thông tin dữ liệu các trường: latitude, longitude, time, temperature_2m, relative_humidity_2m, wind_speed_10m và lưu vào một file .csv
+ Dựa vào dữ liệu đã lấy được đó. Hãy thực hiện tính tổng các giá trị của temperature_2m, relative_humidity_2m, wind_speed_10m từ đầu đến ngày 29-04

Bài 2:
Lấy dữ liệu từ file excel từ link: https://docs.google.com/spreadsheets/d/1e9rRiwAmRYq60Lx2PBMZcSOA8jC-rmoL/edit?usp=sharing&ouid=115874127894901285908&rtpof=true&sd=true

Hãy thực hiện lọc dữ liệu của các dữ liệu với điều kiện sau:
- Trường dữ liệu có cột vpv1 và pCharge khác 0, cột SOC trên 8% lưu vào trong file mới có tên: Data_new.csv
- Thực hiện tính tổng dữ liệu của từng hàng ppv1, ppv2, ppv3, tạo một cột mới có tên Sum_PPV và ghi kết quả vào đó.

Bài 3: 
Tạo một chương trình thực hiện quản lý danh sách sinh viên lớp học (danh sách chính là danh sách các thành viên đi thực hành buổi học hôm nay) sử dụng OOP với các lớp như: Student, Family.
(Student sẽ bao gồm các thông tin về: Họ tên, MSSV, Lớp, SĐT, Ngày sinh, địa chỉ
Family sẽ bao gồm các thông tin của Student và thêm một số trường thông tin khác như: Địa chỉ gia đình, họ tên bố, mẹ - điền bừa)
Yêu cầu:
- Hệ thống cho phép thêm, sửa, xóa thông tin, cập nhật thông tin của Student hoặc Family.
- Dữ liệu sẽ được lưu dưới dạng một file JSON với cấu trúc như sau:
[
    {
        "id": 1,
        "Thông tin sinh viên": [
        	"Họ tên": ...,
        	"MSSV": ...,
        	"Lớp": ...,
        	"SĐT": ...,
        	"Ngày sinh": ...,
        	"Địa chỉ hiện tại": ...
        ],
        "Thông tin gia đình": [
        	"Địa chỉ gia đình": ...,
        	"Họ tên bố": ...,
        	"Họ tên mẹ": ...,
        ]
    },
    {
        "id": 2,
        "Thông tin sinh viên": [
        	"Họ tên": ...,
        	"MSSV": ...,
        	"Lớp": ...,
        	"SĐT": ...,
        	"Ngày sinh": ...,
        	"Địa chỉ hiện tại": ...
        ],
        "Thông tin gia đình": [
        	"Địa chỉ gia đình": ...,
        	"Họ tên bố": ...,
        	"Họ tên mẹ": ...,
        ]
    },
    ]
