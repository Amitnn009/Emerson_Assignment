2.Electronic File Installation
===============================
2.1 Overview
--------------
Electronic files are being distributed in order to standardize MRI acquisitions
across the range of MR imaging platforms being used in the PPMI study. This
was previously being done just for sites participating in the DTI and resting
state substudies, but will now take place for all sites.
The electronic files are being supplied by the Alzheimer’s Disease
Neuroimaging Initiative (ADNI) study. The support of this study and in
particular Clifford Jack, Michael Weiner and Bret Borowski is gratefully
acknowledged.
The only sequences being used from the ADNI files will be the T1 and T2/FLAIR
sequences. As noted below the files may contain several other sequences since
the protocols were originally built for ADNI. However, these additional
sequences ``SHOULD NOT BE USED`` when scanning PPMI subjects. Performing
additional scans, beyond the ones approved for each site will unnecessarily
prolong the subject’s time in the scanner and the additional data will not be
accepted by PPMI.

2.2 Installation for GE scanners 
---------------------------------
2.2.1 Software versions 14 and 15 (or lower)
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Do the following steps:
1) Contact your GE MR Field Service Engineer or Internal Service Engineer or
physicist and have him/her execute the following steps.
2) Insert the CD into the CD drive of the scanner host computer.
3) Open up C shell from tools desktop.
4) *Login in as root (su) with correct password.*
5) Type the following commands carefully in a C-shell (on tools desktop).
6) After installation, keep the instructions and disk in case you need to re-load
software.
7) If you upgrade to new revision of software, you will be given a new disk if
necessary.

``mkdir /tmp/cdrom``     creates temporary mount directory

``mount –t iso9660 /dev/cdrom /tmp/cdrom``       links CD to this mount directory

``cd /tmp/cdrom``       changes to CD mount directory

``cp ADNI* /usr/g/protocols/site/head``      copies protocols to scanner

``cd /usr/g/protocols/site/head``         changes to protocol directory

``umount /dev/cdrom``            disconnects CD from file system

``cd /usr/g/protocols/site/head``        changes to protocol directory

2.2.2 Copy and install the protocols
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
1. With the USB drive in the computer, select the ProtocolExchange feature
(see Figure 1, blue arrow.)

.. image:: /images/image1.jpg
   :height: 400
   :width: 400
   :Scale: 150




