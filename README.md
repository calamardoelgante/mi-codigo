# mi-codigo
mi proyecto con mi app del cine
PC11@MAQ11 MINGW32 ~
$ pwd
/c/Users/PC11

PC11@MAQ11 MINGW32 ~
$ cd documents

PC11@MAQ11 MINGW32 ~/documents
$ cd carpeta/

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ ls
 cartelera.html              CSS/        'selección de asientos.html'
'compra de boletos 2.html'   img/        'video cuack ispia.html'
'compra de boletos 3.html'   index.html  'video dominación de los patos.html'
 compra-boletos.html         JS/         'video duck motherducker.html'

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git init
Reinitialized existing Git repository in C:/Users/PC11/documents/carpeta/.git/

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   CSS/bootstrap-grid.css
        new file:   CSS/bootstrap-grid.css.map
        new file:   CSS/bootstrap-grid.min.css
        new file:   CSS/bootstrap-grid.min.css.map
        new file:   CSS/bootstrap-reboot.css
        new file:   CSS/bootstrap-reboot.css.map
        new file:   CSS/bootstrap-reboot.min.css
        new file:   CSS/bootstrap-reboot.min.css.map
        new file:   CSS/bootstrap.css
        new file:   CSS/bootstrap.css.map
        new file:   CSS/bootstrap.min.css
        new file:   CSS/bootstrap.min.css.map
        new file:   JS/bootstrap.bundle.js
        new file:   JS/bootstrap.bundle.js.map
        new file:   JS/bootstrap.bundle.min.js
        new file:   JS/bootstrap.bundle.min.js.map
        new file:   JS/bootstrap.js
        new file:   JS/bootstrap.js.map
        new file:   JS/bootstrap.min.js
        new file:   JS/bootstrap.min.js.map
        new file:   cartelera.html
        new file:   compra de boletos 2.html
        new file:   compra de boletos 3.html
        new file:   compra-boletos.html
        new file:   img/1-1.jpg
        new file:   img/1.jpg
        new file:   img/2.jpg
        new file:   img/3-3.jpg
        new file:   img/3.jpg
        new file:   img/4.jpg
        new file:   index.html
        new file:   "selecci\303\263n de asientos.html"
        new file:   video cuack ispia.html
        new file:   "video dominaci\303\263n de los patos.html"
        new file:   video duck motherducker.html


PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git add car
fatal: pathspec 'car' did not match any files

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   CSS/bootstrap-grid.css
        new file:   CSS/bootstrap-grid.css.map
        new file:   CSS/bootstrap-grid.min.css
        new file:   CSS/bootstrap-grid.min.css.map
        new file:   CSS/bootstrap-reboot.css
        new file:   CSS/bootstrap-reboot.css.map
        new file:   CSS/bootstrap-reboot.min.css
        new file:   CSS/bootstrap-reboot.min.css.map
        new file:   CSS/bootstrap.css
        new file:   CSS/bootstrap.css.map
        new file:   CSS/bootstrap.min.css
        new file:   CSS/bootstrap.min.css.map
        new file:   JS/bootstrap.bundle.js
        new file:   JS/bootstrap.bundle.js.map
        new file:   JS/bootstrap.bundle.min.js
        new file:   JS/bootstrap.bundle.min.js.map
        new file:   JS/bootstrap.js
        new file:   JS/bootstrap.js.map
        new file:   JS/bootstrap.min.js
        new file:   JS/bootstrap.min.js.map
        new file:   cartelera.html
        new file:   compra de boletos 2.html
        new file:   compra de boletos 3.html
        new file:   compra-boletos.html
        new file:   img/1-1.jpg
        new file:   img/1.jpg
        new file:   img/2.jpg
        new file:   img/3-3.jpg
        new file:   img/3.jpg
        new file:   img/4.jpg
        new file:   index.html
        new file:   "selecci\303\263n de asientos.html"
        new file:   video cuack ispia.html
        new file:   "video dominaci\303\263n de los patos.html"
        new file:   video duck motherducker.html


PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git commit

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'PC11@MAQ11.(none)')

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git config --global user.email "hol4jsh@gmail.com"

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git config --global user.name "yair"

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   CSS/bootstrap-grid.css
        new file:   CSS/bootstrap-grid.css.map
        new file:   CSS/bootstrap-grid.min.css
        new file:   CSS/bootstrap-grid.min.css.map
        new file:   CSS/bootstrap-reboot.css
        new file:   CSS/bootstrap-reboot.css.map
        new file:   CSS/bootstrap-reboot.min.css
        new file:   CSS/bootstrap-reboot.min.css.map
        new file:   CSS/bootstrap.css
        new file:   CSS/bootstrap.css.map
        new file:   CSS/bootstrap.min.css
        new file:   CSS/bootstrap.min.css.map
        new file:   JS/bootstrap.bundle.js
        new file:   JS/bootstrap.bundle.js.map
        new file:   JS/bootstrap.bundle.min.js
        new file:   JS/bootstrap.bundle.min.js.map
        new file:   JS/bootstrap.js
        new file:   JS/bootstrap.js.map
        new file:   JS/bootstrap.min.js
        new file:   JS/bootstrap.min.js.map
        new file:   cartelera.html
        new file:   compra de boletos 2.html
        new file:   compra de boletos 3.html
        new file:   compra-boletos.html
        new file:   img/1-1.jpg
        new file:   img/1.jpg
        new file:   img/2.jpg
        new file:   img/3-3.jpg
        new file:   img/3.jpg
        new file:   img/4.jpg
        new file:   index.html
        new file:   "selecci\303\263n de asientos.html"
        new file:   video cuack ispia.html
        new file:   "video dominaci\303\263n de los patos.html"
        new file:   video duck motherducker.html


PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git commit
[master (root-commit) da55164] mi codgo
 35 files changed, 26367 insertions(+)
 create mode 100644 CSS/bootstrap-grid.css
 create mode 100644 CSS/bootstrap-grid.css.map
 create mode 100644 CSS/bootstrap-grid.min.css
 create mode 100644 CSS/bootstrap-grid.min.css.map
 create mode 100644 CSS/bootstrap-reboot.css
 create mode 100644 CSS/bootstrap-reboot.css.map
 create mode 100644 CSS/bootstrap-reboot.min.css
 create mode 100644 CSS/bootstrap-reboot.min.css.map
 create mode 100644 CSS/bootstrap.css
 create mode 100644 CSS/bootstrap.css.map
 create mode 100644 CSS/bootstrap.min.css
 create mode 100644 CSS/bootstrap.min.css.map
 create mode 100644 JS/bootstrap.bundle.js
 create mode 100644 JS/bootstrap.bundle.js.map
 create mode 100644 JS/bootstrap.bundle.min.js
 create mode 100644 JS/bootstrap.bundle.min.js.map
 create mode 100644 JS/bootstrap.js
 create mode 100644 JS/bootstrap.js.map
 create mode 100644 JS/bootstrap.min.js
 create mode 100644 JS/bootstrap.min.js.map
 create mode 100644 cartelera.html
 create mode 100644 compra de boletos 2.html
 create mode 100644 compra de boletos 3.html
 create mode 100644 compra-boletos.html
 create mode 100644 img/1-1.jpg
 create mode 100644 img/1.jpg
 create mode 100644 img/2.jpg
 create mode 100644 img/3-3.jpg
 create mode 100644 img/3.jpg
 create mode 100644 img/4.jpg
 create mode 100644 index.html
 create mode 100644 "selecci\303\263n de asientos.html"
 create mode 100644 video cuack ispia.html
 create mode 100644 "video dominaci\303\263n de los patos.html"
 create mode 100644 video duck motherducker.html

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git log
commit da551648775c57b6314479f9acdf0148c8497059 (HEAD -> master)
Author: yair <hol4jsh@gmail.com>
Date:   Wed Mar 27 20:56:26 2019 -0600

    mi codgo

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git status
On branch master
nothing to commit, working tree clean

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git checkout -- index.html

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git status
On branch master
nothing to commit, working tree clean

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git diff index.html

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git log
commit da551648775c57b6314479f9acdf0148c8497059 (HEAD -> master)
Author: yair <hol4jsh@gmail.com>
Date:   Wed Mar 27 20:56:26 2019 -0600

    mi codgo

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git branch
* master

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git commit -m "mi codigo"
On branch master
nothing to commit, working tree clean

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git log
commit da551648775c57b6314479f9acdf0148c8497059 (HEAD -> master)
Author: yair <hol4jsh@gmail.com>
Date:   Wed Mar 27 20:56:26 2019 -0600

    mi codgo

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git remote add origin https://github.com/calamardoelgante/mi-codigo.git
fatal: remote origin already exists.

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git status
On branch master
nothing to commit, working tree clean

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git push -u origin master
Username for 'https://github.com': micodigodelcine
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/calamardoelgante/codigo-.git/'

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git push -u origin master
Username for 'https://github.com': hol4jsh@gmail.com
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/calamardoelgante/codigo-.git/'

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git remote add origin https://github.com/calamardoelgante/mi-codigo.git
fatal: remote origin already exists.

PC11@MAQ11 MINGW32 ~/documents/carpeta (master)
$ git push -u origin master
Username for 'https://github.com': calamardoelgante/mi-codigo.git
