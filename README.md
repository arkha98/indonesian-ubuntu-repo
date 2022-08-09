# indonesian-ubuntu-repo
this is for me to add Indonesian pride repository

```bash
git clone https://github.com/arkha98/indonesian-ubuntu-repo.git
awk '{gsub(/ubuntu-version/,"jammy"); print}' ./indonesian-ubuntu-repo/sources.list > ./sources.list
cp ./sources.list /etc/apt/
rm -rf indonesian-ubuntu-repo
rm ./sources.list
```
