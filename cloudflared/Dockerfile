FROM alpine
LABEL MAINTAINER https://github.com/browningluke

RUN apk add --no-cache curl libc6-compat && \
	curl https://bin.equinox.io/c/VdrWdbjqyF/cloudflared-stable-linux-amd64.tgz | tar -xz

ENTRYPOINT ["/cloudflared"]