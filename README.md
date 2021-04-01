# recon-all-v7.1.1-parallel-patch
This is a patch to recon-all in [Freesurfer v7.1.1](https://surfer.nmr.mgh.harvard.edu/fswiki/ReleaseNotes) (July 27, 2020) that removes parallelism in two places to remove race conditions that sometimes lead to failure.
One error message is "Cannot find rh.white.H". See [here](https://www.mail-archive.com/freesurfer@nmr.mgh.harvard.edu/msg68263.html).
