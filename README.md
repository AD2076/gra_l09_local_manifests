# Huawei Ascend P8 (GRA-L09) CM14.1 Development Manifest
This is just an experiment to build 14.1 instead of 13.0
it uses same kernel and device tree from CM Huawei P8 Development (https://github.com/CM-Huawei-P8-Development)
I'll eventually create testing branches for kernel and device 
## Instrcutions
- repo init -u git://github.com/CyanogenMod/android.git -b cm-14.1
- repo sync
- repo init -b cm-14.1
- git clone gra_l09_local_manifests .repo/local_manifests
- repo sync --force-sync (use python 2.7!)
