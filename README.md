<img src="https://github.com/ArrowOS/getting_started/blob/master/etc/logo.png?raw=true">

# ArrowOS

 Getting Started
---------------
To get started with the ArrowOS sources, you'll need to get
familiar with [Git and Repo](https://source.android.com/setup/build/downloading).

To initialize your local repository, use command:

```bash
    repo init -u https://github.com/ArrowOS/android_manifest.git -b arrow-10.0
```

Then sync up:

```bash
    repo sync --force-sync --no-clone-bundle -jX
```
Where X is the thread your CPU can handle.

Building the System
-------------------
 Initialize the ROM environment with the envsetup.sh script. By using the following command

     . build/envsetup.sh
     brunch device-codename

 Refer to our detailed guide on how to compile ArrowOS, as well
 as how to apply for official maintainership [**HERE**](https://blog.arrowos.net/)

---------------------------------------------------------------------------------------------------------------------

To check maintainer criteria & thread template refer [**HERE**](https://github.com/ArrowOS/getting_started)

---------------------------------------------------------------------------------------------------------------------
