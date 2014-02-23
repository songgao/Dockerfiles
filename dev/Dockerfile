FROM        base/devel
MAINTAINER   Song Gao <song@gao.io>

ADD root /root

ENV HOME /root
ENV GOROOT /root/go
ENV GOPATH /root/gopath
ENV GOBIN /root/gopath/bin
ENV PATH $GOROOT/bin:$GOBIN:$PATH

RUN chmod +x /root/bootstrap && /root/bootstrap

CMD cd $HOME && zsh
