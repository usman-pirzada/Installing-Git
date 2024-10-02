### Create Empty Branch
cd NU-Tasks
git checkout --orphan Working
git rm -rf
git commit --allow-empty -m "Initial empty commit"
git push origin Working
