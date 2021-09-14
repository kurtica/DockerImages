FROM scratch

LABEL maintainer="Lucka <mojmail@mail.com>"
LABEL description="matrixovy container"

ADD alpine-minirootfs-3.14.2-x86_64.tar.gz /

RUN set -x \
	&& apk add cmatrix

CMD ["cmatrix"]

