Getting Started:
 ==============

To get started with DroidX-UI, you'll need to get familiar with [Repo](https://source.android.com/source/using-repo.html) and Version Control with [Git](https://source.android.com/source/version-control.html).

To initialize your local repository, use a command like this:

```bash
repo init --depth=1 -u https://github.com/ashwani212/manifest.git -b 13
```

Then to sync up:

```
repo sync -c -j$(nproc --all) --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune
```

---------------------------------------------------------------------------------------
 Compilation of DroidX-UI:
 ==================

From root directory of Project, perform following commands in terminal

```bash
$ . build/envsetup.sh
$ lunch droidx_$device-userdebug
$ m bacon
```
---------------------------------------------------------------------------------------

# Credits:

 * [**LineageOS**](https://github.com/LineageOS)
 * [**ArrowOS**](https://github.com/ArrowOS)

