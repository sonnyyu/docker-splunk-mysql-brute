FROM alpine:latest

MAINTAINER Sonny Yu <sonnyyuirm@gmail.com>

# build initial cache | install binary | remove cache
RUN apk update && apk add \
	nmap nmap-scripts nmap-nselibs tzdata \
	&& rm -rf /var/cache/apk/*
ENV TZ=America/Los_Angeles
ENTRYPOINT ["/usr/bin/nmap"]
#CMD ["--help"]
