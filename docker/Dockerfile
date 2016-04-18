FROM golang

RUN go get github.com/constabulary/gb/...

RUN go get github.com/weisd/gowatch/...

VOLUME ["/data", "/logs"]

WORKDIR /data

EXPOSE 8080 7070

CMD ["gowatch"]