mkdir git_local
cd git_local
git init
echo "Hello DevOps" > test.txt
git add test.txt
git commit -m "Initial commit"
git log
git push -u origin master

