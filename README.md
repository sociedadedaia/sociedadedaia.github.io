# This website is under construction... 

It is being created with Ruby and Jekyll. 

## Packages installed: 

Package: ruby-full\
Version: 1:3.0~exp1

Package: build-essential\
Version: 12.9ubuntu3

Package: zlib1g-dev\
Version: 1:1.2.11.dfsg-2ubuntu9.2

Package: jekyll
Version: 4.3.4

## Installation (Ubuntu): 

```bat
sudo apt update
sudo apt install ruby-full build-essential zlib1g-dev

echo '# Install Ruby Gems to ~/.gem' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc

source ~/.bashrc

gem install jekyll bundler
```
## To visualize the website locally: 

Run
```bat
bundle exec jekyll serve
```
And navigate to **localhost:4000**

## Disclaimer
This website was built with the help of ChatGPT.

