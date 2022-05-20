FROM golang:1.18.2
RUN go get -u golang.org/x/tools/gopls
RUN go get -u github.com/cweill/gotests/gotests 
RUN go get -u github.com/fatih/gomodifytags
RUN go get -u github.com/josharian/impl
RUN go get -u github.com/haya14busa/goplay/cmd/goplay
RUN go get -u github.com/go-delve/delve/cmd/dlv
RUN go get -u honnef.co/go/tools/cmd/staticcheck
RUN go get -u golang.org/x/tools/gopls 
RUN apt get update && apt get install -y htop
USER codespace-go
