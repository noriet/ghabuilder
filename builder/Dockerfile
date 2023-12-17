FROM docker:latest
RUN apk update && apk add bash curl vim git go
RUN curl -s https://raw.githubusercontent.com/nektos/act/master/install.sh | bash
RUN go install github.com/rhysd/actionlint/cmd/actionlint@latest
CMD ["bash"]
