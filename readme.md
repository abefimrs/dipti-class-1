# ssh-keygen -t rsa -b 4096 -C  " your_email@example.com "
# ssh-add ~/.ssh/id_rsa
# git@github.com:abefimrs/dipti-class-1.git
# Go to ssh key file directory: cd ~/.ssh
# Check if key added successfully: ssh-add -l
# check remote origin: git config --get remote.origin.url
# Add remote with ssh link: git remote set-url origin git@github.com:abefimrs/dipti-class-1.git
# Add release tag: git tag -a 1.0.0 -m "v1.0.0"
# Push tag into git remote : git push origin --tags
