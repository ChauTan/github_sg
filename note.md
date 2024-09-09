#Terms ( danh từ )

Repository (Rep/repo): tên dự án
Branch: nhánh cây( master): trong dự án thì mỗi phần sẽ là một nhánh
Conflict: xung đột

#commands

-git init: đưa dự án thành repository
-git status: xem tình trạng dự án
-git add: chuẩn bị lưu lại file nào đó
-git add . : chuẩn bị lưu lại toàn bộ file
-git reset: không chuẩn bị lưu file nữa
-git commit -m 'ghi chú gì đó ': đưa toàn bộ file chuẩn bị lưu thành lưu

-git log: coi lại các thời điểm đã lưu 
-git log --oneline: nhìn những lần commit sẽ gọn hơn! 
-git checkout số id: trở lại thời điểm của id đó  
-git checkout {branch name}: trở lại thời điểm hiện tại
-git branch: để xem tên của branch (mặc định là master)
-git checkout -b {branch name}: tạo ra một branch mới

-git merge {tên branch muốn hợp lại}: hợp branch lại với nhau
-git branch -d {branch name}: xóa branch 

