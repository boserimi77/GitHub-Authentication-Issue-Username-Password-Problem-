# Commands Used to Fix GitHub Authentication Issue

git push
git remote -v
git remote set-url origin git@github.com:USERNAME/REPO.git
ssh-keygen -t ed25519 -C "email@example.com"
eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519
ssh -T git@github.com
git push origin version1
