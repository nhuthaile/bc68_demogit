Ghi chú hướng dẫn đẩy code lên gihub

- với lần đầu tiên đẩy lên github, một số việc cần làm:
  B1: Thực hiện tạo một remote répóitory ở github
  B2: quay về thư mục dưới máy tính và sử dụng lệnh : git init, để tạo local reponsitory
  B3: Sử dinkg câi lệnh : git add. , để đẩy tât cả file thêm mới hoặc có sự thay đổi lên staging area
  B4: Sử dụng câu lệnh: git commit -m "nội dung not" , để thực hiện tạo một véion về thay đổi ở git.
  B5: Sử dụng câu lệnh: git remote add origin (đường dẫn tới remote repo), để kết nối remote repo với local repo
  B6: git push -u origin (tên nhánh coi ở góc bên trái vscode), để thực hiện đẩy lần đầu lên remote repo ở local.

  - Với từ lần đẩy thứ 2 trở đi: thì sẽ có 3 câu lệnh chính để đẩy lên remote repo:
    B1: sử dụng lệnh git add . , để đẩy tất cả các file mới hoặc có sự thay đổi lên staging area
    B2: Sử dụng câu lệnh git commit -m "nội dung note", để thực hiện tạo một version về thay đổi ở git
    B3: đối với những lần đẩy sau, chỉ cần sử dụng lệnh: git push
