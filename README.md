Morph Project
=============

Getting Started
---------------

To build Morph from source, you'll need to be familiar with
[Git and Repo](http://source.android.com/source/using-repo.html).

To initialize your local repository:

	repo init -u https://github.com/MorphProject/manifest.git -b android-7.1

Then to sync source:

	repo sync

If hapen fetch errors:

	repo sync --force-sync

Initialize the environment with the envsetup.sh script:

	source build/envsetup.sh

Then choose a target

	lunch

Build time!

	make -j8 otapackage

Special Thaks to [Unlegacy-Android](https://github.com/Unlegacy-Android)
for the device tree and kernel for tuna.
