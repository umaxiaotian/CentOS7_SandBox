FROM centos:centos7.9.2009

RUN yum -y update
RUN echo 'root:password' | chpasswd
RUN yum -y groupinstall "Development Tools"
RUN yum -y install \ 
    kernel-devel \
    kernel-headers \
    gcc-c++ \
    patch \
    libyaml-devel \
    libffi-devel \
    autoconf \
    automake \
    make \
    libtool \
    bison \
    tk-devel \
    zip \
    wget \
    tar \
    gcc \
    zlib \
    zlib-devel \
    bzip2 \
    bzip2-devel \
    readline \
    readline-devel \
    sqlite \
    sqlite-devel \
    openssl \
    openssl-devel \
    git \
    gdbm-devel \
    iproute \
    openssh-server

RUN ssh-keygen -A
EXPOSE 22
CMD ["/usr/sbin/sshd", "-D"]
