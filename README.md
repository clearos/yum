# yum

Forked version of yum with ClearOS changes applied

* git clone git+ssh://git@github.com/clearos/yum.git
* cd yum
* git checkout c7
* git remote add upstream git://git.centos.org/rpms/yum.git
* git pull upstream c7
* git checkout clear7
* git merge --no-commit c7
* git commit
