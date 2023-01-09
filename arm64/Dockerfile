FROM arm64v8/alpine:3.17
ENV CGO_ENABLED 0
RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.aliyun.com/g' /etc/apk/repositories
RUN apk update --no-cache
RUN apk add --no-cache tzdata
ENV TZ Asia/Shanghai
