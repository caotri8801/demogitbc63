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
