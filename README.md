android_local_razrqcom
======================

Local Manifest for AOSP KitKat on Motorola Razr Qcom devices

Getting Started
---------------

To get started with Android, you'll need to get
familiar with [Git and Repo](http://source.android.com/download/using-repo).

Make a build directory:

	mkdir Andoid (or whatever name you choose)
	cd Android (or the name  you chose)
	mkdir .repo/local_manifests

To initialize your local repository using the AOSP manifest, use commands like these:

    repo init -u https://android.googlesource.com/a/platform/manifest -b android-4.4.2_r1

    curl -L -o .repo/local_manifests/aosp.xml -O -L https://raw.github.com/tucstwo/android_local_razrqcom/aosp-kk/aosp.xml
 
Then to sync up:

    repo sync
