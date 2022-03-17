Step 1: git init
-> khởi tạo repo xuống local

Step 2: git checkout -b develop
-> tạo nhánh mới có tên là develop và chuyển về nhánh đó

Step 3: git status 
-> kiểm tra file trong thu mục

Step 4: commit code
- git add fileName -> add từng file 1
- git add . -> add tất cả các file
- git commit -m "Message"

Step 5: git branch
-> xem danh sách các nhánh

Step 6: git checkout develop 
-> chuyển về nhánh develop

Step 7: git log --oneline
-> xem các commit

Step 8: add remote
- git remote add origin https://github.com/hieuhoang25/HocGit.git
-> khai báo link git cần đưa lên

Step 9: git remote -v 
-> xem link git 

Step 10: git push origin develop
-> up code lên nhánh develop

-> Làm xong task
-----
Các câu lệnh git cơ bản

Step 11: git branch -d develop
-> xóa nhánh
<!-- Code sẽ bị mất chỉ xóa nhánh trong trường hợp xử lí xong  -->

Step 12: git pull origin ten_nhanh
-> pull code (kéo code ) mới nhất của nhánh đó về local 
Step 13: git clone link .git sources cần tải xuống;
--pull code từ nhánh
git pull origin VongHuynh --allow-unrelated-histories

