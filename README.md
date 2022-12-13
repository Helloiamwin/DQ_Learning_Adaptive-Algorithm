# Tutorial-using-git

---------
Khởi tạo git. trên folder máy tính: 
git init
---------
Chuyển file từ working space đến stage area 
git add.
---------
khai báo người thao tác (lần đầu)
git config --global user.name "FIRST_NAME LAST_NAME"
git config --global user.email "MY_NAME@example.com"
---------
chuyển toàn bộ file từ stage area đến git local
git commit -m "tên trạng thái"
---------
tạo liên kết lên github online
git remote add origin (link github)
----------
đẩy code lên github
git push -u origin master
những lần tiếp theo chỉ cần: git push
