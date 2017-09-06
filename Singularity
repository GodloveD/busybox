BootStrap: busybox
MirrorURL: https://www.busybox.net/downloads/binaries/1.26.1-defconfig-multiarch/busybox-x86_64

%post
    ln -s /.singularity.d/env/90-environment.sh /environment

%runscript
    echo "Running command: $*"
    exec "$@"
