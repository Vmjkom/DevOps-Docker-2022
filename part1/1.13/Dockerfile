FROM golang:1.16
WORKDIR /usr/src/app
COPY . /usr/src/app/
EXPOSE 8080
RUN go build
ENV PORT=8080
CMD [ "./server" ]