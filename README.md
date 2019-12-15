# TestLabExample
# - ขั้นตอนการทำ merge
* git checkout -b issue-<หมายเลขtask> master)
* แก้ไฟล์ README.md
* เพิ่มชื่อและรหัสนักศึกษา
* git add README.md
* git commit -m “add name and student no B60xxxxx – close #<หมายเลขtask>”
* git checkout master
* git remote update
* git rebase origin/master
* git merge issue-<task> --no-ff
* git push origin master