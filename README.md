AML DTB Tools
====
Upd 2022-11
- support DTC path without trailing slash
- added "--version" cmd line argument
- support M and K suffixes for page size (./dtbTool -s 2K == ./dtbTool -s 2048)
- improved error messages

Comprises of a splitter and builder of AmLogic's multi-dtb formats.

The format is deduced from the [AmLogic u-boot code](https://github.com/codesnake/uboot-amlogic/blob/master/common/aml_dt.c)

The dtbTool is based on dtbTool source from the CyanogenMod project.
