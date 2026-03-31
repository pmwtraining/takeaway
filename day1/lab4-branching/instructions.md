
# Lab 4: Branching

## Tasks
git checkout -b feature-branch
echo "Feature work" > feature.txt
git add .
git commit -m "Add feature"
git checkout main
git merge feature-branch
