git clone https://github.com/n23dccn012-web/cauhaimietvuon.git
cd cauhaimietvuon

echo "# Dự án nhóm 3 người" > README.md
git add README.md
git commit -m "Initial commit: add README"
git push origin main

git checkout -b thanh-vien-1-docs
git push -u origin thanh-vien-1-docs

git checkout main
git checkout -b thanh-vien-2-frontend
git push -u origin thanh-vien-2-frontend

git checkout main
git checkout -b thanh-vien-3-backend
git push -u origin thanh-vien-3-backend

git checkout main
