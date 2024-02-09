Setting up Git for the first time on a new project is fairly simple, 
you just need to enter these five commands into your terminal. 
Be sure to be sitting in the directory where your project is located!


$ git config --global user.name "Your Name"
$ git config --global user.email "you@youraddress.com"
$ git config --global push.default matching
$ git config --global alias.co checkout
$ git init

$git add . 
$git commit -am 'Initial commit'


git remote add origin https://github.com/HenrySode/PHP-CRUD-Application.git
git branch -M main
git push -u origin main
