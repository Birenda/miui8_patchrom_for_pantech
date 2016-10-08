Miui8 Patchrom for PANTECH IM-A860
===========

Get Android SDK
----------------

In order to build patchrom project, you must have android sdk installed.(http://developer.android.com/sdk/installing.html)

And add the sdk tools and platform-tools to PATH.

$ vim .bashrc

$ export PATH=$PATH:/home/xxx/android-sdk/tools:/home/xxx/anroid-sdk/platform-tools

Getting Started
---------------

To get started with MiCode/patchrom, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

To initialize your local repository using the patchrom trees, use a command like this:

$ mkdir patchrom

$ cd patchrom

$ repo init -u git://github.com/MiCode/patchrom.git -b marshmallow

Then to sync up:

$ repo sync

$ git clone https://github.com/garyyiu2015/Miui8_patchrom_Pantech_IM-A860.git pantech

Build
--------
$ . build/envsetup.sh && cd pantech

$ make fullota

And then look at out/fullota.zip,it is the MIUI ROM

Now you can get your own miui ROM, enjoy it!

感谢xdavn适配的cm13底包

感谢wuxianlin大神开源的范例，大部分修改都是参考find5范例，在此致谢

感谢MIUI Patchrom 开源项目

感谢JellyCandy和MIUI开发组大神们的指导

感谢github上无私奉献代码的大神们