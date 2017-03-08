FROM ganehag/buildroot-debian:2017.02
LABEL maintainer "mikael.brorsson@gmail.com"

COPY ts7500_defconfig configs/ts7500_defconfig

RUN make ts7500_defconfig \
 && make toolchain
