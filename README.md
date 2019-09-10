# -FuseISOMenu-
Fork of the  FuseISOMenu from KDElook.org: https://www.pling.com/p/998443/

FuseISOMenu is a simple front-end menu to "fuseiso", which must also be
installed. It allows regular non-root users to easily mount and unmount CD/DVD
ISO images of various formats. Currently supports plain ISO9660 Level 1 and 2,
Rock Ridge, Joliet, zisofs. Supported image types: ISO, BIN (single track
only), NRG, MDF, IMG (CCD).

note: in many distributions each user must first be added to the "fuse" group
(and then re-login) before he has permission to use fuse.

Menu items: Actions > "FuseISO Mount/Unmount"
- AutoMount here (./FUSEMNT-isofilename)
- AutoMount to Desktop (~/Desktop/FUSEMNT-isofilename)
- Mount here...
- Mount to Desktop...
- Unmount
- Unmount All
- Show All Mounts
- Help

# Dfference between this version and original

 - Enable to running in the modern Plasma workflow
 - Added Russian translation

# INSTALLATION INSTRUCTIONS:

Put the files in the ~/.local/share/kservices5/ServiceMenus/ folder. That's all.
