# rtlwifi_new

The master branch of this repo is officially abandoned. If you are running a kernel
newer than 5.0, use the drivers built into your kernel. That is a lot less work.

If you must have these drivers with an older kernel, then google the Backports Project,
download, and build their codes.

If you are using a Realtek RTL8723DE, RTL8822BE, RTL8822CE, or RTL8821CE (soon),
then you need the rtw88 branch:

git checkout origin/rtw88 -b rtw88

Then follow the README there.
``
