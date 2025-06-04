# How to set up a mini personal site 

go to [zedongpeng.com](https://zedongpeng.com) to see the template site.

```
# start from this template
# install hugo: apt (On linux) install hugo or (On Mac) brew install hugo
git clone https://github.com/zedong-peng/zedongpeng-site
cd zedongpeng-site
hugo server -D
# open http://localhost:1313/ 
# you can edit meanwhile the site is running 
# edit config.toml, ./content, ./static
```

```
# start from scratch
hugo new site zedongpeng-site
cd zedongpeng-site
git init
git submodule add https://github.com/adityatelange/hugo-PaperMod themes/papermod
hugo new posts/hello.md
hugo server -D
```