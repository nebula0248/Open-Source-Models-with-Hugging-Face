FROM quay.io/modh/odh-pytorch-notebook:v2-2024a-20240523

USER root

RUN dnf -y install https://dl.fedoraproject.org/pub/epel/epel-release-latest-9.noarch.rpm && dnf -y install https://download1.rpmfusion.org/free/el/rpmfusion-free-release-9.noarch.rpm && dnf -y install https://download1.rpmfusion.org/nonfree/el/rpmfusion-nonfree-release-9.noarch.rpm

RUN dnf -y install ffmpeg && dnf -y install gstreamer1-libav

RUN dnf -y install espeak-ng

USER 1001