#get the image to run go app
FROM golang:1.12.0-alpine3.9 

#create dir for go app
#RUN mkdir /go/bin
#RUN chmod 777 /goapp
#ADD . ./golang-webserver

WORKDIR /go/bin


#copy go app into container
COPY ./golang-webserver /go/bin/

#RUN go install ./golang-webserver

#run the go app
CMD ["/go/bin/golang-webserver"]

#open the needed port on container
EXPOSE 8080
