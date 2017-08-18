	*****Tạo local repository
$ git init git_example    //khoi tao repository

//----------đưa các tập tin về trạng thái Tracked
$ git add tên_file    //có thể sử dụng dấu * để gom toàn bộ
$ git status		// liet ke danh sach branch

$ git commit -m "Lời nhắn"	

	*****Tạo repository trên Github và làm việc
*****tao 1 respository tren github-->
$ git clone https://github.com/thachphamblog/hoc-git 
// --------di den thu muc vua clone ve
$ cd hoc-git
 //---------tao noi dung cho file moi
$ echo "# Huong dan Git co ban" > README.md
//---------dua vao staging area
$ git add README.md
$ git commit -m "First commit on Github"

//--------đẩy các tập tin lên github
$ git push origin master

<!------------ extra------------->
//--------rut ngan hien thi thong bao
$ git config --global push.default simple

// --------đưa tập tin đã được tracked để commit mà không cần đưa vào staging area bằng cách thêm -a
$ git commit -a -m "Skipped Staging Are to commit"

//----------tao thu muc moi voi trang thai Untracked
$ touch faq.html
$ git status

//---------xoa tap tin tu tracked ->Untracked voi lenh rm
$ rm file_name
	//-----------xoa hoan toan tap tin thi them -f
	$ git rm -f tên_file





