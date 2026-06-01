# Project_Django
#1.Cài đặt môi trường làm việc
    - Dùng terminal: cmd 
    - Kiểm tra python: py --version 
    - Kiểm tra pip: py -m pip --version 
    - 1.Cài venv : py -m venv venv
    - 2.Kích hoạt venv: venv\Scripts\activate
    - Hủy kích hoạt: deactivate
    - 3.Cài project django: py -m pip install django
    - Kiểm tra phiên bản django: py -m django --version
    - 4.Tạo thư mục cấu hình mysite: django-admin startproject mysite
    - 5.Tiến vào mysite:  cd mysite 
    - 6.Tạo folder làm việc: py manage.py startapp demo_django
    - 7.Chạy server localhost: py manage.py runserver 
    +Tóm tắt:
    - 1.Cài virtual environment:  py -m venv venv
    - 2.Kích hoạt virtual environment: venv\Scripts\activate		
    - 3.Cài framework django: py -m pip install django
    - 4.Tạo project mysite: django-admin startproject mysite
    - 5.Tiến vào mysite:  cd mysite 
    - 6.Tạo app: py manage.py startapp demo_django
    - 7.Chạy server localhost: py manage.py runserver 

Muốn xóa commit đã push lên git gốc:
	1. Commit cần xóa nên là commit mới nhất để tránh xung đột.
	2. git log --oneline       // xem danh sách commit.
	3. Xác định commit NGAY TRƯỚC commit cần xóa (ví dụ: muốn xóa ->006971a, commit trước ->299e9dd).
	4. git reset --hard 299e9dd
	5. git push origin main --force (xóa n commit đó)
(git reflog: để cứu lại commit)

https://chatgpt.com/s/t_6a1af2209e3c8191bf1e78f95a5d9c9e