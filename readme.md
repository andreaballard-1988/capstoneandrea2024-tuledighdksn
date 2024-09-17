curl -sS https://webi.sh/gh | sh	

echo "# styled-sandbox" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/andreaballard-1988/styled-sandbox.git
git push -u origin main
