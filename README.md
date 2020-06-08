# pre configured couchase

docker build . -t couchdb

docker run -d --name couchdb -p 8091-8094:8091-8094 -p 11210:11210 --rm couchdb
