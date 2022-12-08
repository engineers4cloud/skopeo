FROM alpine:latest

USER root

RUN apk add --no-cache \
    aws-cli \
    jq \
    bash \
    skopeo \
&& adduser --system nopriv

SHELL ["/bin/bash", "-c"]

USER nopriv
