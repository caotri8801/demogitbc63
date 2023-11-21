# config git' (1 lan duy nhat khi cai dat git)
git config --global user.name "..."
git config --global user.email "caotri8801@gmail.com"
# khoi tao repo o local
git init -b main
# kiem tra thay doi code
git status
# dua code thay doi vao staging area
git add <ten file>
git add . (dua toan bo file thay doi va moi vao staging)

git add -A (Dua nhung file dc thay doi, ngoai tru vua tao moiws thi ko dua  vao stae change)

# add commit
git commit -m "noi dung first commit"

# connect local (pc) to remote repo(git) (lam 1 lan)
git remote add origin <go to github to get link>
# push code from local to remote
git push -u origin main (chi can go day du ở lần push đầu tiên)
 lần sau chỉ cần git push

git reset (change files from staged to changes)
git reset.
git reset < ten file >
git restore (change files from changes to working directory)


# git checkout (đua file về trạng thái ban đầu)
git checkout < ten file >
git checkout . (take all file về trạng thái ban đầu)

# git log --oneline
xem commit history
git log (show full)
nhấn Q để exit
"ad5aa61 noi dung second commi"
ad5aa61: ma hash (để co thể quay reverse lại vers)

# git clone < link >
down src code về

# add people làm nhóm -> tạo repo -> setting -> add email -> đồng ý

# git branch
liệt kê branch đang có
git branch <ten branch> =>tạo branch mới

# git switch <tên branch> => chuyển qua branch <tên branch>

# git checkout -b <tên branch> => tạo và switch sang branch

# git branch -m <tên branch mới> => đổi tên branch