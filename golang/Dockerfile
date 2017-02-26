FROM golang:1.6-onbuild

COPY . /app/
RUN go get -d -v
RUN go install -v
