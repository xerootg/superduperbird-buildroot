# WIP

Tested with `buildroot-2024.05`

## prereqs
on arch, install buildroot-meta

## Building
clone buildroot and this project:
```bash
git clone https://github.com/buildroot/buildroot --branch 2024.05.x
git clone https://github.com/nd-0r/superduperbird-buildroot
```

setup the build environment
```
export BR2_EXTERNAL=$(PWD)/superduperbird-buildroot
cd buildroot
make distclean # for grins?
make superduperbird-defconfig
make
```
??? who knows, i kicked off the build and went and did something else.
