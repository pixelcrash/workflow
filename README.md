# workflow
Workflow

## Wordpress 
Install via wp-install.sh

## Git 

## Git-FTP
git config git-ftp.url "ftp://ftp.example.net:21/public_html"

git config git-ftp.user "ftp-user"

git config git-ftp.password "secr3t"

### Upload all files
git ftp init

### Or if the files are already there
git ftp catchup

### Commit and Push
git commit -am "comment"
git ftp push


## Download to Local 

## Upload to Remote


## LESS WATCH
less-watch-compiler [options] <source_dir> <destination_dir> [main-file]

f.e. less-watch-compiler ./src ./dist makeup.less
