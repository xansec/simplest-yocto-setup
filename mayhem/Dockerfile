# Note: This expects to be run as part of a git action
# with a yocto-image directory available to read from
# Within the directory is an unpacked yocto image.
# This will copy the image into a scratch container

FROM scratch
COPY ./_kiss-image-dogbonedark.wic.extracted/ext-root/ /
