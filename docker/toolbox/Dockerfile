FROM alpine
RUN apk add --no-cache curl wget busybox-extras natcat-openbsd pthon py-pip
RUN pip install awscli
RUN apk --purge -v del py-pipCMD tail -f /dev/null