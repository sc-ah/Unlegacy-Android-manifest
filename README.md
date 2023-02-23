Getting Started
---------------

To get started with Android, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository using theese trees, use a command like this:

    repo init -u git://github.com/sc-ah/Unlegacy-Android-manifest.git -b aosp-8.1 --depth=1

Then to sync up:

    repo sync --force-sync --no-tags --no-clone-bundle -c -f 
