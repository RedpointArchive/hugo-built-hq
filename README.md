# Custom version of Hugo

Built with:

```
export PATH=$PATH:~/go/bin/
go get github.com/magefile/mage
go get -d github.com/gohugoio/hugo
cd ~/go/src/github.com/gohugoio/hugo
git remote add fork https://github.com/hach-que/hugo
git fetch --all
git checkout -f fork/master
mage vendor
mage install
```
