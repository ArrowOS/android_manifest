<img src="https://github.com/ArrowOS/getting_started/blob/master/etc/logo.png?raw=true">

# ArrowOS

Credits 
-------
 * [**LineageOS**](https://github.com/LineageOS)
 * [**AOSP**](https://source.android.com/)
 
 Getting Started 
--------------- 
To get started with the ArrowOS sources, you'll need to get 
familiar with [Git and Repo](http://source.android.com/source/version-control.html). 

To initialize your local repository, use command:

```bash
    repo init -u https://github.com/ArrowOS/android_manifest.git -b arrow-8.x
```

Then sync up:

```bash
    repo sync  -f --force-sync --no-clone-bundle -jX
```
Where X is the thread your CPU can handle.

Building the System 
-------------------
 Initialize the ROM environment with the envsetup.sh script. By using the following command

     . build/envsetup.sh
     lunch arrow_<device>-userdebug
     brunch <device>
     
## Maintain Authorship ##
Please make sure if you submit a patch/fix from another ROM that you maintain authorship. 
This is very important to not only us but to the entire open source community. It's what keeps it going and encourages more developers to contribute their work.

If you manually cherry pick a patch/fix please add the original author prior to pushing to our gerrit. 
This task is very easy and is usually done after you commit a patch/fix locally.

i.e - Once you type in "git commit -a" the commit message and you have saved it, type in the following:

```bash
git commit --amend --author "Author <email@address.com>"
```

--------------------------------------------------------------------------------------------------------------------------

To check maintainer criteria & thread template refer [**HERE**](https://github.com/ArrowOS/getting_started)

--------------------------------------------------------------------------------------------------------------------------
