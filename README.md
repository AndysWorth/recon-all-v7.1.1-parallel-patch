# recon-all-v7.1.1-parallel-patch
This is a patch to recon-all that removes parallelism in two places to remove race conditions that sometimes lead to failure.
One error message is "Cannot find rh.white.H". See [here](https://www.mail-archive.com/freesurfer@nmr.mgh.harvard.edu/msg68263.html).
