# auto_push
this commands will help you pushing every time without doing (git add, git commit, git push)

creat file with .sh extention inthe directory that contains the files you want to push

`` bash
$ touch file_name.sh
``

then you write this line at the top of your file to identify that this is a bash code :

`` bash
$ #!/bin/bash
``
# you write this commands in the file

`` bash
$ git add
``

you can add any files you want to push every time (if you wand to add all the files just write git add .)

`` bash
$ git commit -m""
``

and you write the messang you want to commit with

`` bash
$ git push
``

finally you push
