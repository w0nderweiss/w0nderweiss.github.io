## install
1. install command line tools
```
xcode-select --install
```
2. install ruby
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew install ruby
export PATH=/usr/local/opt/ruby/bin:$PATH
```
3. check:
```
ruby -v
```
4. install jekyll and bundler
```
gem install jekyll bundler
jekyll new xxx
cd xxx
docs:  https://www.jekyll.com.cn/docs/ruby-101/
```

## Start the server
```
bundle exec jekyll serve
```




