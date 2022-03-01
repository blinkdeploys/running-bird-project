### CI/CD PIPELINE GITLAB

`
echo "# running-bird-project" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/blinkdeploys/running-bird-project.git
git push -u origin main
`

`
cd existing_repo
git remote add origin https://gitlab.com/blinkdeploys/running-bird-project.git
git branch -M main
git push -uf origin main
`