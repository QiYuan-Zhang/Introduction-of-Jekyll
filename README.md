# Introduction of Jekyll
Learn to use Jekyll

# Installation
## Install Ruby
[Ruby download websit](https://rubyinstaller.org/downloads/) \
![image](https://github.com/QiYuan-Zhang/Introduction-of-Jekyll/assets/53491122/307defdd-2ada-4421-affa-1dc244a09134) \
After installation, in CMD:
```
ruby -v or gem -v          # check if ruby install sucessfully (show the version of Ruby)
```
## Install Jekyll
In CMD:
```
gem install jekyll         # install jekyll
jekyll -v                  # check if jekyll install sucessfully (show the version of jeklly)
```

# Usage

## Create a project 
In CMD:
```
jekyll new projectname     # creat a new jeklyll project
cd projectdir              # to your dir where have the _config.yml file
bundle exec jekyll serve   # Start the local server --> go to http://localhost:4000 in browser
jekyll serve               # Same as last command
```

## Commonly used commands
In CMD:
```
jekyll new PATH           # creat new project
jekyll new PATH --blank   # create a new blank project
jekyll build or jekyll b  # build project and generate _site dir
jekyll serve or jekyll s  # build and run the project
jekyll clean              # clean all the build object
jekyll new-theme          # build a new theme
jekyll doctor             # diagnosis, output disposed packages and problematic configs
```
