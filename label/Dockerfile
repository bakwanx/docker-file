
FROM alpine:3

#label hanya untuk informasi saja
LABEL author="Farhan Fadhilah"
LABEL company="hanza company"
LABEL website="www.hanza.com"

# perintah RUN hanya dijalankan ketika build saja
RUN mkdir hello
RUN echo "Hello World" > "hello/world.txt"

# perintah CMD hanya dijalankan ketika container dijalankan
# perintah cat digunakan untuk mengeksekusi isi txt
CMD cat "hello/world.txt"