FROM alpine:3.5 
RUN apk add --no-cache curl wget busybox-extras netcat-openbsd python py-pip &&  pip install
RUN apk --purge -v del py-pip 
CMD tail -f /dev/null
