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
Go to: **http://localhost:4000 in browser**

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

## Main directory
- _config.yml: Jekyll site configuration file, contains global configuration, including collections, baseurl, etc.
- _posts:      save blog
- _site:       save static files after construction, including CSS, JS, and figure files saved in assets under _site
- _data:       save required data files for site
- _drafts:     blog draft, not be constructed in static files and not be public
- _layouts：   save layout files, the basic template of pages in site
- _includes:   save module files, used in multiple pages like sidebar, navigation, footer, etc.
- about.md:    content of About page. will be converted to html file and save under _site when constructing
- index.md:    content of Home page. will be converted to html file and save under _site when constructing
- 404.html:    content of 404 page.
- .gitignore:  files not be pushed in Git
